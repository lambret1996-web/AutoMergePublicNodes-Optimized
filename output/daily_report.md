# AutoNodes 每日报告

生成时间：2026-09-15 06:36:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 90569 |
| 去重后节点数 | 25507 |
| TCP 可达数 | 3000 |
| 真测通过数 | 512 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25507 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 83.1 |
| geo | 1.5 |
| probe | 316.1 |
| real_test | 346.7 |
| tcp | 40.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 51 | 32 | 19 | 62.7% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 169 | 157 | 12 | 92.9% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 30 | 22 | 8 | 73.3% |
| vless | 488 | 281 | 207 | 57.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 68 |
| speed:TimeoutError | 34 |
| geo:ClientOSError | 33 |
| 204:ProxyError | 29 |
| cn-block:TimeoutError | 25 |
| 204:TimeoutError | 23 |
| speed:ClientOSError | 17 |
| cn-block:ClientOSError | 15 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 2 |
| 204:ServerDisconnectedError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5667 |
| ConnectionRefusedError | 945 |
| gaierror | 448 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.868 | prefer | 292 | 0.808 | 1549 |
| Surfboard-tg-mixed | 0.745 | prefer | 165 | 0.667 | 7543 |
| mheidari-all | 0.646 | observe | 134 | 0.567 | 21540 |
| ermaozi | 0.632 | observe | 50 | 0.62 | 425 |
| DeltaKronecker-all | 0.572 | observe | 116 | 0.491 | 5972 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 133 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 8044 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.491 | 57 | 59 | 116 |
| mheidari-all | 0.567 | 76 | 58 | 134 |
| ermaozi | 0.62 | 31 | 19 | 50 |
| Surfboard-tg-mixed | 0.667 | 110 | 55 | 165 |
| Au1rxx-base64 | 0.808 | 236 | 56 | 292 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21540 | yes | 4.63 | 0 |
| SoliSpirit-all | 8973 | yes | 4.66 | 0 |
| Epodonios-all | 8044 | yes | 4.82 | 0 |
| Surfboard-tg-mixed | 7543 | yes | 3.74 | 0 |
| barry-far-vless | 6333 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 6114 | yes | 3.27 | 0 |
| DeltaKronecker-all | 5972 | yes | 5.13 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.16 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 2.85 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.24 | 0 |

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
| geo | 102 |
| 204 | 55 |
| speed | 51 |
| cn-block | 42 |
