# AutoNodes 每日报告

生成时间：2026-09-26 04:59:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 96648 |
| 去重后节点数 | 26495 |
| TCP 可达数 | 3000 |
| 真测通过数 | 516 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26495 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 154.7 |
| geo | 1.5 |
| probe | 355.5 |
| real_test | 524.6 |
| tcp | 43.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 44 | 13 | 31 | 29.5% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 182 | 168 | 14 | 92.3% |
| socks | 8 | 5 | 3 | 62.5% |
| trojan | 35 | 17 | 18 | 48.6% |
| vless | 740 | 295 | 445 | 39.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 202 |
| speed:TimeoutError | 90 |
| cn-block:ClientOSError | 57 |
| geo:ClientOSError | 48 |
| 204:ProxyError | 45 |
| 204:TimeoutError | 22 |
| speed:ClientOSError | 22 |
| cn-block:TimeoutError | 21 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5848 |
| ConnectionRefusedError | 950 |
| gaierror | 419 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.901 | prefer | 272 | 0.838 | 1634 |
| Surfboard-tg-mixed | 0.866 | prefer | 68 | 0.794 | 7217 |
| mheidari-all | 0.425 | observe | 632 | 0.345 | 22526 |
| ermaozi | 0.357 | observe | 33 | 0.333 | 352 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| ermaozi-get_subscribe | 0.267 | observe | 14 | 0.286 | 375 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7682 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8923 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.144 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 7 | 7 |
| ermaozi-get_subscribe | 0.286 | 4 | 10 | 14 |
| ermaozi | 0.333 | 11 | 22 | 33 |
| mheidari-all | 0.345 | 218 | 414 | 632 |
| Surfboard-tg-mixed | 0.794 | 54 | 14 | 68 |
| Au1rxx-base64 | 0.838 | 228 | 44 | 272 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22526 | yes | 4.44 | 0 |
| SoliSpirit-all | 8923 | yes | 2.45 | 0 |
| Epodonios-all | 7682 | yes | 3.74 | 0 |
| Surfboard-tg-mixed | 7217 | yes | 2.91 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.34 | 0 |
| barry-far-vless | 6063 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 5837 | yes | 3.05 | 0 |
| DeltaKronecker-all | 5452 | yes | 4.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 1.2 | 0 |
| mahdibland-V2RayAggregator | 4304 | yes | 2.28 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 250 |
| speed | 113 |
| cn-block | 79 |
| 204 | 71 |
