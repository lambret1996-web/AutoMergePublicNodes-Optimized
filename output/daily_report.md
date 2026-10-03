# AutoNodes 每日报告

生成时间：2026-10-03 04:31:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 98934 |
| 去重后节点数 | 27172 |
| TCP 可达数 | 3000 |
| 真测通过数 | 471 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27172 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| generate | 77.4 |
| geo | 1.2 |
| probe | 293.5 |
| real_test | 446.8 |
| tcp | 47.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 3 | 1 | 75.0% |
| http | 23 | 16 | 7 | 69.6% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 162 | 147 | 15 | 90.7% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 11 | 11 | 0 | 100.0% |
| vless | 605 | 276 | 329 | 45.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 154 |
| speed:TimeoutError | 87 |
| geo:ClientOSError | 37 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 14 |
| 204:ProxyConnectionError | 8 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6555 |
| ConnectionRefusedError | 1172 |
| gaierror | 458 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | prefer | 273 | 0.923 | 1751 |
| ermaozi | 0.706 | prefer | 23 | 0.696 | 645 |
| Surfboard-tg-mixed | 0.646 | observe | 81 | 0.568 | 7256 |
| mheidari-all | 0.431 | observe | 439 | 0.351 | 23323 |
| ermaozi-get_subscribe | 0.289 | observe | 3 | 0.667 | 516 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5276 |
| Epodonios-all | 0.255 | observe | 0 | None | 7743 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9351 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.351 | 154 | 285 | 439 |
| Surfboard-tg-mixed | 0.568 | 46 | 35 | 81 |
| ermaozi-get_subscribe | 0.667 | 2 | 1 | 3 |
| ermaozi | 0.696 | 16 | 7 | 23 |
| Au1rxx-base64 | 0.923 | 252 | 21 | 273 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23323 | yes | 5.89 | 0 |
| SoliSpirit-all | 9351 | yes | 1.87 | 0 |
| Epodonios-all | 7743 | yes | 3.57 | 0 |
| Surfboard-tg-mixed | 7256 | yes | 4.06 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.16 | 0 |
| barry-far-vless | 6214 | yes | 1.52 | 0 |
| Surfboard-tg-vless | 5980 | yes | 4.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 5276 | yes | 1.01 | 0 |
| DeltaKronecker-all | 4981 | yes | 6.71 | 0 |
| mahdibland-V2RayAggregator | 4357 | yes | 1.18 | 0 |

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
| geo | 191 |
| speed | 108 |
| 204 | 33 |
| cn-block | 22 |
