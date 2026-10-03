# AutoNodes 每日报告

生成时间：2026-10-03 16:01:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 99542 |
| 去重后节点数 | 27331 |
| TCP 可达数 | 3000 |
| 真测通过数 | 334 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27331 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| generate | 83.8 |
| geo | 1.5 |
| probe | 189.4 |
| real_test | 173.4 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 23 | 21 | 2 | 91.3% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 87 | 77 | 10 | 88.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 29 | 18 | 11 | 62.1% |
| vless | 261 | 203 | 58 | 77.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 24 |
| 204:ProxyError | 8 |
| 204:ProxyConnectionError | 6 |
| geo:TimeoutError | 5 |
| geo:ClientOSError | 3 |
| speed:ClientOSError | 3 |
| speed:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6513 |
| ConnectionRefusedError | 1153 |
| gaierror | 406 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.919 | prefer | 261 | 0.851 | 1778 |
| ermaozi | 0.906 | prefer | 23 | 0.913 | 656 |
| Surfboard-tg-mixed | 0.796 | prefer | 107 | 0.72 | 7404 |
| mheidari-all | 0.705 | prefer | 22 | 0.636 | 23342 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5192 |
| Epodonios-all | 0.255 | observe | 0 | None | 7883 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9374 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6035 |
| barry-far-vless | 0.255 | observe | 0 | None | 6273 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.636 | 14 | 8 | 22 |
| Surfboard-tg-mixed | 0.72 | 77 | 30 | 107 |
| Au1rxx-base64 | 0.851 | 222 | 39 | 261 |
| ermaozi | 0.913 | 21 | 2 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23342 | yes | 6.15 | 0 |
| SoliSpirit-all | 9374 | yes | 3.96 | 0 |
| Epodonios-all | 7883 | yes | 3.12 | 0 |
| Surfboard-tg-mixed | 7404 | yes | 4.04 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.29 | 0 |
| barry-far-vless | 6273 | yes | 1.6 | 0 |
| Surfboard-tg-vless | 6035 | yes | 5.48 | 0 |
| DeltaKronecker-all | 5207 | yes | 6.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 1.38 | 0 |
| mahdibland-V2RayAggregator | 4335 | yes | 3.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| cn-block | 27 |
| geo | 10 |
| speed | 6 |
