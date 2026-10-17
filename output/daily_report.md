# AutoNodes 每日报告

生成时间：2026-10-17 03:39:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99741 |
| 去重后节点数 | 27733 |
| TCP 可达数 | 3000 |
| 真测通过数 | 612 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27733 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| generate | 99.3 |
| geo | 1.7 |
| probe | 322.8 |
| real_test | 385.0 |
| tcp | 49.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 3 | 1 | 75.0% |
| http | 51 | 22 | 29 | 43.1% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 173 | 160 | 13 | 92.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 84 | 77 | 7 | 91.7% |
| vless | 505 | 329 | 176 | 65.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 51 |
| 204:ProxyError | 40 |
| geo:ClientOSError | 38 |
| speed:ClientOSError | 29 |
| speed:TimeoutError | 22 |
| cn-block:TimeoutError | 11 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 9 |
| 204:ClientOSError | 7 |
| speed:ProxyError | 5 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7090 |
| ConnectionRefusedError | 1045 |
| OSError | 235 |
| gaierror | 207 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.949 | prefer | 533 | 0.871 | 1993 |
| Surfboard-tg-mixed | 0.668 | observe | 66 | 0.591 | 7128 |
| mheidari-all | 0.56 | observe | 23 | 0.478 | 24092 |
| DeltaKronecker-all | 0.503 | observe | 154 | 0.422 | 4946 |
| ermaozi | 0.491 | observe | 52 | 0.462 | 702 |
| ninja-vless | 0.438 | observe | 5 | 0.8 | 1791 |
| ermaozi-get_subscribe | 0.382 | observe | 3 | 1.0 | 601 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5024 |
| tg-Farah_VPN | 0.263 | observe | 1 | 1.0 | 200 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1993 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.422 | 65 | 89 | 154 |
| ermaozi | 0.462 | 24 | 28 | 52 |
| mheidari-all | 0.478 | 11 | 12 | 23 |
| Surfboard-tg-mixed | 0.591 | 39 | 27 | 66 |
| ninja-vless | 0.8 | 4 | 1 | 5 |
| Au1rxx-base64 | 0.871 | 464 | 69 | 533 |
| tg-Farah_VPN | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24092 | yes | 8.31 | 0 |
| SoliSpirit-all | 10039 | yes | 4.11 | 0 |
| Epodonios-all | 7692 | yes | 7.47 | 0 |
| Surfboard-tg-mixed | 7128 | yes | 4.9 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.4 | 0 |
| barry-far-vless | 5847 | yes | 2.45 | 0 |
| Surfboard-tg-vless | 5602 | yes | 5.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 2.24 | 0 |
| DeltaKronecker-all | 4946 | yes | 6.75 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 2.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 89 |
| 204 | 60 |
| speed | 56 |
| cn-block | 23 |
