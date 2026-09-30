# AutoNodes 每日报告

生成时间：2026-09-30 05:30:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96719 |
| 去重后节点数 | 27034 |
| TCP 可达数 | 3000 |
| 真测通过数 | 480 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27034 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 44.3 |
| geo | 1.5 |
| probe | 346.1 |
| real_test | 458.3 |
| tcp | 45.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 3 | 1 | 75.0% |
| http | 60 | 51 | 9 | 85.0% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 173 | 155 | 18 | 89.6% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 16 | 8 | 8 | 50.0% |
| vless | 612 | 237 | 375 | 38.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 157 |
| speed:TimeoutError | 76 |
| speed:ClientOSError | 67 |
| geo:ClientOSError | 40 |
| 204:ProxyError | 27 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6544 |
| ConnectionRefusedError | 1000 |
| gaierror | 327 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.853 | prefer | 293 | 0.788 | 1657 |
| ermaozi | 0.83 | prefer | 58 | 0.828 | 335 |
| Surfboard-tg-mixed | 0.825 | prefer | 53 | 0.755 | 7024 |
| DeltaKronecker-all | 0.503 | observe | 12 | 0.583 | 5528 |
| mheidari-all | 0.393 | observe | 467 | 0.313 | 22586 |
| ermaozi-get_subscribe | 0.38 | observe | 5 | 0.8 | 353 |
| tg-oneclickvpnkeys | 0.361 | observe | 3 | 1.0 | 74 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| Epodonios-all | 0.255 | observe | 0 | None | 7591 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.313 | 146 | 321 | 467 |
| DeltaKronecker-all | 0.583 | 7 | 5 | 12 |
| Surfboard-tg-mixed | 0.755 | 40 | 13 | 53 |
| Au1rxx-base64 | 0.788 | 231 | 62 | 293 |
| ermaozi-get_subscribe | 0.8 | 4 | 1 | 5 |
| ermaozi | 0.828 | 48 | 10 | 58 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22586 | yes | 5.1 | 0 |
| SoliSpirit-all | 9348 | yes | 2.13 | 0 |
| Epodonios-all | 7591 | yes | 4.47 | 0 |
| Surfboard-tg-mixed | 7024 | yes | 2.62 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.01 | 0 |
| barry-far-vless | 5895 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 5656 | yes | 4.08 | 0 |
| DeltaKronecker-all | 5528 | yes | 3.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 5314 | yes | 1.87 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 1.49 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 199 |
| speed | 143 |
| 204 | 49 |
| cn-block | 24 |
