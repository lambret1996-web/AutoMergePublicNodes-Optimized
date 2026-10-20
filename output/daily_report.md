# AutoNodes 每日报告

生成时间：2026-10-20 16:39:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94292 |
| 去重后节点数 | 26481 |
| TCP 可达数 | 3000 |
| 真测通过数 | 329 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26481 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 77.5 |
| geo | 1.5 |
| probe | 219.4 |
| real_test | 237.3 |
| tcp | 45.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 35 | 18 | 17 | 51.4% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 109 | 99 | 10 | 90.8% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 48 | 33 | 15 | 68.8% |
| vless | 224 | 163 | 61 | 72.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 22 |
| speed:TimeoutError | 19 |
| 204:ProxyError | 18 |
| speed:ClientOSError | 8 |
| geo:TimeoutError | 6 |
| geo:ClientOSError | 5 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6621 |
| ConnectionRefusedError | 1054 |
| OSError | 238 |
| gaierror | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.88 | prefer | 68 | 0.809 | 23236 |
| Au1rxx-base64 | 0.834 | prefer | 293 | 0.782 | 1348 |
| DeltaKronecker-all | 0.759 | prefer | 26 | 0.692 | 3519 |
| zhangkai | 0.501 | observe | 26 | 0.5 | 31 |
| Surfboard-tg-mixed | 0.489 | observe | 9 | 0.667 | 6911 |
| Epodonios-all | 0.335 | observe | 1 | 1.0 | 7384 |
| ermaozi-get_subscribe | 0.322 | observe | 8 | 0.5 | 429 |
| chromego_merge | 0.264 | observe | 1 | 1.0 | 227 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 79 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.5 | 4 | 4 | 8 |
| zhangkai | 0.5 | 13 | 13 | 26 |
| Surfboard-tg-mixed | 0.667 | 6 | 3 | 9 |
| DeltaKronecker-all | 0.692 | 18 | 8 | 26 |
| Au1rxx-base64 | 0.782 | 229 | 64 | 293 |
| mheidari-all | 0.809 | 55 | 13 | 68 |
| Epodonios-all | 1.0 | 1 | 0 | 1 |
| chromego_merge | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23236 | yes | 3.48 | 0 |
| SoliSpirit-all | 10086 | yes | 3.58 | 0 |
| Epodonios-all | 7384 | yes | 3.11 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 2.19 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.36 | 0 |
| barry-far-vless | 5732 | yes | 0.92 | 0 |
| Surfboard-tg-vless | 5515 | yes | 2.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 1.63 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 1.78 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 40 |
| speed | 29 |
| cn-block | 24 |
| geo | 12 |
