# AutoNodes 每日报告

生成时间：2026-10-16 03:49:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99761 |
| 去重后节点数 | 27953 |
| TCP 可达数 | 3000 |
| 真测通过数 | 498 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27953 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 80.6 |
| geo | 1.4 |
| probe | 284.2 |
| real_test | 434.4 |
| tcp | 49.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 43 | 28 | 15 | 65.1% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 150 | 135 | 15 | 90.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 44 | 38 | 6 | 86.4% |
| vless | 525 | 281 | 244 | 53.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 106 |
| speed:TimeoutError | 39 |
| speed:ClientOSError | 34 |
| 204:TimeoutError | 25 |
| 204:ProxyError | 21 |
| geo:ClientOSError | 20 |
| cn-block:ClientOSError | 12 |
| cn-block:TimeoutError | 11 |
| cn-block:ProxyError | 5 |
| 204:ClientOSError | 4 |
| speed:ClientPayloadError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7177 |
| ConnectionRefusedError | 1028 |
| gaierror | 248 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.838 | prefer | 557 | 0.759 | 1991 |
| ermaozi | 0.687 | observe | 42 | 0.667 | 693 |
| Surfboard-tg-mixed | 0.349 | observe | 3 | 0.667 | 7135 |
| mheidari-all | 0.337 | observe | 165 | 0.255 | 23985 |
| DeltaKronecker-all | 0.305 | observe | 10 | 0.3 | 5147 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1991 |
| Epodonios-all | 0.255 | observe | 0 | None | 7647 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9903 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.255 | 42 | 123 | 165 |
| DeltaKronecker-all | 0.3 | 3 | 7 | 10 |
| Surfboard-tg-mixed | 0.667 | 2 | 1 | 3 |
| ermaozi | 0.667 | 28 | 14 | 42 |
| Au1rxx-base64 | 0.759 | 423 | 134 | 557 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23985 | yes | 3.91 | 0 |
| SoliSpirit-all | 9903 | yes | 3.48 | 0 |
| Epodonios-all | 7647 | yes | 4.05 | 0 |
| Surfboard-tg-mixed | 7135 | yes | 2.84 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.49 | 0 |
| barry-far-vless | 5878 | yes | 1.57 | 0 |
| Surfboard-tg-vless | 5628 | yes | 3.02 | 0 |
| DeltaKronecker-all | 5147 | yes | 4.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 4235 | yes | 0.93 | 0 |

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
| geo | 128 |
| speed | 76 |
| 204 | 50 |
| cn-block | 28 |
