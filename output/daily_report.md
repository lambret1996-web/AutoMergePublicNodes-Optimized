# AutoNodes 每日报告

生成时间：2026-09-16 18:30:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 89351 |
| 去重后节点数 | 24450 |
| TCP 可达数 | 3000 |
| 真测通过数 | 388 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24450 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 72.4 |
| geo | 1.5 |
| probe | 283.3 |
| real_test | 202.2 |
| tcp | 42.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 15 | 9 | 6 | 60.0% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 142 | 132 | 10 | 93.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 17 | 7 | 10 | 41.2% |
| vless | 296 | 217 | 79 | 73.3% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 27 |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 14 |
| 204:TimeoutError | 12 |
| geo:TimeoutError | 12 |
| speed:ClientOSError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6109 |
| ConnectionRefusedError | 907 |
| gaierror | 288 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.978 | prefer | 57 | 0.912 | 17820 |
| Au1rxx-base64 | 0.947 | prefer | 241 | 0.884 | 1665 |
| DeltaKronecker-all | 0.741 | prefer | 110 | 0.664 | 6081 |
| Surfboard-tg-mixed | 0.642 | observe | 71 | 0.563 | 7470 |
| ermaozi | 0.49 | observe | 12 | 0.667 | 353 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4234 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5115 |
| Epodonios-all | 0.255 | observe | 0 | None | 7938 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9095 |

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
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| Surfboard-tg-mixed | 0.563 | 40 | 31 | 71 |
| DeltaKronecker-all | 0.664 | 73 | 37 | 110 |
| ermaozi | 0.667 | 8 | 4 | 12 |
| Au1rxx-base64 | 0.884 | 213 | 28 | 241 |
| mheidari-all | 0.912 | 52 | 5 | 57 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17820 | yes | 5.15 | 0 |
| SoliSpirit-all | 9095 | yes | 3.88 | 0 |
| Epodonios-all | 7938 | yes | 4.27 | 0 |
| Surfboard-tg-mixed | 7470 | yes | 3.77 | 0 |
| barry-far-vless | 6195 | yes | 1.5 | 0 |
| DeltaKronecker-all | 6081 | yes | 3.85 | 0 |
| Surfboard-tg-vless | 5979 | yes | 4.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 4234 | yes | 2.89 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.62 | 0 |

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
| geo | 41 |
| 204 | 32 |
| cn-block | 24 |
| speed | 12 |
