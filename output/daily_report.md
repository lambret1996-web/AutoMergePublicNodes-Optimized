# AutoNodes 每日报告

生成时间：2026-10-05 04:50:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 98824 |
| 去重后节点数 | 27506 |
| TCP 可达数 | 3000 |
| 真测通过数 | 539 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27506 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 74.6 |
| geo | 1.5 |
| probe | 296.7 |
| real_test | 447.6 |
| tcp | 46.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 1 | 2 | 33.3% |
| http | 62 | 29 | 33 | 46.8% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 128 | 117 | 11 | 91.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 88 | 85 | 3 | 96.6% |
| vless | 637 | 293 | 344 | 46.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 160 |
| speed:TimeoutError | 78 |
| 204:ProxyError | 54 |
| geo:ClientOSError | 37 |
| cn-block:TimeoutError | 18 |
| 204:ProxyConnectionError | 16 |
| speed:ClientOSError | 14 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6290 |
| ConnectionRefusedError | 1023 |
| gaierror | 447 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 371 | 0.892 | 1883 |
| Surfboard-tg-mixed | 0.858 | prefer | 25 | 0.8 | 7178 |
| ermaozi | 0.497 | observe | 62 | 0.468 | 694 |
| mheidari-all | 0.417 | observe | 461 | 0.336 | 23195 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5173 |
| Epodonios-all | 0.255 | observe | 0 | None | 7673 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9258 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5736 |

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
| downweight | DeltaKronecker-all | 0.249 | 10 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.2 | 2 | 8 | 10 |
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.336 | 155 | 306 | 461 |
| ermaozi | 0.468 | 29 | 33 | 62 |
| Surfboard-tg-mixed | 0.8 | 20 | 5 | 25 |
| Au1rxx-base64 | 0.892 | 331 | 40 | 371 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23195 | yes | 6.81 | 0 |
| SoliSpirit-all | 9258 | yes | 3.92 | 0 |
| Epodonios-all | 7673 | yes | 2.42 | 0 |
| Surfboard-tg-mixed | 7178 | yes | 5.0 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.62 | 0 |
| barry-far-vless | 6057 | yes | 2.45 | 0 |
| Surfboard-tg-vless | 5736 | yes | 4.22 | 0 |
| DeltaKronecker-all | 5267 | yes | 6.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 5173 | yes | 2.69 | 0 |
| mahdibland-V2RayAggregator | 4365 | yes | 0.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 197 |
| speed | 92 |
| 204 | 81 |
| cn-block | 25 |
