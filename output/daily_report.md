# AutoNodes 每日报告

生成时间：2026-10-22 16:57:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96380 |
| 去重后节点数 | 26688 |
| TCP 可达数 | 3000 |
| 真测通过数 | 333 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26688 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 80.4 |
| geo | 1.5 |
| probe | 238.4 |
| real_test | 232.0 |
| tcp | 45.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 42 | 14 | 28 | 33.3% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 150 | 132 | 18 | 88.0% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 52 | 43 | 9 | 82.7% |
| vless | 190 | 128 | 62 | 67.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 28 |
| 204:ProxyError | 25 |
| speed:ClientOSError | 16 |
| cn-block:TimeoutError | 12 |
| speed:TimeoutError | 11 |
| 204:ProxyConnectionError | 7 |
| geo:ClientOSError | 6 |
| speed:ProxyError | 4 |
| cn-block:ClientOSError | 4 |
| geo:TimeoutError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6667 |
| ConnectionRefusedError | 1038 |
| OSError | 243 |
| gaierror | 208 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.958 | prefer | 47 | 0.894 | 24062 |
| Au1rxx-base64 | 0.892 | prefer | 241 | 0.834 | 1529 |
| Surfboard-tg-mixed | 0.709 | prefer | 114 | 0.632 | 7066 |
| DeltaKronecker-all | 0.373 | observe | 5 | 0.6 | 3641 |
| ermaozi | 0.364 | observe | 42 | 0.333 | 573 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 7538 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10202 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.333 | 14 | 28 | 42 |
| DeltaKronecker-all | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.632 | 72 | 42 | 114 |
| Au1rxx-base64 | 0.834 | 201 | 40 | 241 |
| mheidari-all | 0.894 | 42 | 5 | 47 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24062 | yes | 5.41 | 0 |
| SoliSpirit-all | 10202 | yes | 3.61 | 0 |
| Epodonios-all | 7538 | yes | 5.72 | 0 |
| Surfboard-tg-mixed | 7066 | yes | 4.73 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.54 | 0 |
| barry-far-vless | 5601 | yes | 1.75 | 0 |
| Surfboard-tg-vless | 5426 | yes | 4.54 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 0.72 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 0.44 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 62 |
| speed | 31 |
| cn-block | 17 |
| geo | 9 |
