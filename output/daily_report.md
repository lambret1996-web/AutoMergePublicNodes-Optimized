# AutoNodes 每日报告

生成时间：2026-09-20 12:29:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 4/101 |
| 原始节点数 | 83790 |
| 去重后节点数 | 23453 |
| TCP 可达数 | 3000 |
| 真测通过数 | 499 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23453 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 79.4 |
| geo | 1.4 |
| probe | 242.3 |
| real_test | 178.4 |
| tcp | 38.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 36 | 14 | 72.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 175 | 159 | 16 | 90.9% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 11 | 5 | 6 | 45.5% |
| vless | 394 | 281 | 113 | 71.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 49 |
| 204:TimeoutError | 25 |
| 204:ProxyError | 21 |
| geo:TimeoutError | 18 |
| cn-block:TimeoutError | 15 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 6 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 3 |
| speed:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5523 |
| ConnectionRefusedError | 796 |
| gaierror | 318 |
| OSError | 14 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.992 | prefer | 272 | 0.93 | 1620 |
| mheidari-all | 0.837 | prefer | 72 | 0.764 | 15979 |
| Surfboard-tg-mixed | 0.74 | prefer | 192 | 0.661 | 7118 |
| ermaozi | 0.715 | prefer | 48 | 0.708 | 365 |
| DeltaKronecker-all | 0.589 | observe | 53 | 0.509 | 6092 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4315 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 89 |
| Epodonios-all | 0.255 | observe | 0 | None | 7603 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9126 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | Surfboard-tg-vless | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-vless | 0.0 | 0 | 5 | 5 |
| 10ium-ScrapeCategorize-Vless | 0.2 | 1 | 4 | 5 |
| DeltaKronecker-all | 0.509 | 27 | 26 | 53 |
| Surfboard-tg-mixed | 0.661 | 127 | 65 | 192 |
| ermaozi | 0.708 | 34 | 14 | 48 |
| mheidari-all | 0.764 | 55 | 17 | 72 |
| Au1rxx-base64 | 0.93 | 253 | 19 | 272 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15979 | yes | 4.84 | 0 |
| SoliSpirit-all | 9126 | yes | 3.64 | 0 |
| Epodonios-all | 7603 | yes | 5.62 | 0 |
| Surfboard-tg-mixed | 7118 | yes | 4.15 | 0 |
| DeltaKronecker-all | 6092 | yes | 4.13 | 0 |
| barry-far-vless | 5960 | yes | 1.53 | 0 |
| Surfboard-tg-vless | 5686 | yes | 3.78 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 1.27 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 2.36 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 67 |
| 204 | 53 |
| cn-block | 23 |
| speed | 9 |
