# AutoNodes 每日报告

生成时间：2026-10-14 04:11:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 98589 |
| 去重后节点数 | 27425 |
| TCP 可达数 | 3000 |
| 真测通过数 | 469 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27425 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 88.3 |
| geo | 1.5 |
| probe | 308.7 |
| real_test | 388.5 |
| tcp | 47.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 44 | 21 | 23 | 47.7% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 127 | 123 | 4 | 96.9% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 77 | 71 | 6 | 92.2% |
| vless | 407 | 238 | 169 | 58.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 88 |
| speed:ClientOSError | 26 |
| 204:ProxyError | 23 |
| geo:ClientOSError | 19 |
| cn-block:TimeoutError | 15 |
| 204:ProxyConnectionError | 10 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| 204:TimeoutError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6380 |
| ConnectionRefusedError | 1052 |
| gaierror | 431 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | prefer | 350 | 0.886 | 1771 |
| Surfboard-tg-mixed | 0.609 | observe | 12 | 0.75 | 7113 |
| mheidari-all | 0.56 | observe | 248 | 0.48 | 24076 |
| zhangkai | 0.494 | observe | 8 | 0.875 | 144 |
| ermaozi-get_subscribe | 0.466 | observe | 41 | 0.439 | 598 |
| DeltaKronecker-all | 0.45 | observe | 12 | 0.5 | 5076 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5086 |
| Epodonios-all | 0.255 | observe | 0 | None | 7613 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9824 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.439 | 18 | 23 | 41 |
| mheidari-all | 0.48 | 119 | 129 | 248 |
| DeltaKronecker-all | 0.5 | 6 | 6 | 12 |
| Surfboard-tg-mixed | 0.75 | 9 | 3 | 12 |
| zhangkai | 0.875 | 7 | 1 | 8 |
| Au1rxx-base64 | 0.886 | 310 | 40 | 350 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24076 | yes | 6.99 | 0 |
| SoliSpirit-all | 9824 | yes | 3.77 | 0 |
| Epodonios-all | 7613 | yes | 6.27 | 0 |
| Surfboard-tg-mixed | 7113 | yes | 4.73 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.13 | 0 |
| barry-far-vless | 5866 | yes | 1.47 | 0 |
| Surfboard-tg-vless | 5621 | yes | 4.18 | 0 |
| 10ium-ScrapeCategorize-Vless | 5086 | yes | 0.91 | 0 |
| DeltaKronecker-all | 5076 | yes | 6.62 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 3.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 109 |
| 204 | 40 |
| speed | 33 |
| cn-block | 22 |
