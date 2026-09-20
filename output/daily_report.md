# AutoNodes 每日报告

生成时间：2026-09-20 06:30:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 87431 |
| 去重后节点数 | 25200 |
| TCP 可达数 | 3000 |
| 真测通过数 | 529 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25200 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 77.1 |
| geo | 1.7 |
| probe | 200.0 |
| real_test | 256.5 |
| tcp | 41.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 53 | 42 | 11 | 79.2% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 183 | 175 | 8 | 95.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 60 | 35 | 25 | 58.3% |
| vless | 396 | 261 | 135 | 65.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 53 |
| geo:ClientOSError | 31 |
| speed:TimeoutError | 25 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 15 |
| cn-block:ClientOSError | 10 |
| speed:ClientOSError | 10 |
| 204:TimeoutError | 10 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5522 |
| ConnectionRefusedError | 903 |
| gaierror | 397 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.938 | prefer | 341 | 0.874 | 1653 |
| mheidari-all | 0.913 | prefer | 34 | 0.853 | 15978 |
| ermaozi | 0.778 | prefer | 53 | 0.774 | 365 |
| Surfboard-tg-mixed | 0.701 | prefer | 196 | 0.622 | 7138 |
| DeltaKronecker-all | 0.537 | observe | 79 | 0.456 | 6421 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4315 |
| xiaoji235-airport-v2ray-all | 0.3 | observe | 5 | 0.4 | 3625 |
| Epodonios-all | 0.255 | observe | 0 | None | 7601 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8785 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| xiaoji235-airport-v2ray-all | 0.4 | 2 | 3 | 5 |
| DeltaKronecker-all | 0.456 | 36 | 43 | 79 |
| Surfboard-tg-mixed | 0.622 | 122 | 74 | 196 |
| ermaozi | 0.774 | 41 | 12 | 53 |
| mheidari-all | 0.853 | 29 | 5 | 34 |
| Au1rxx-base64 | 0.874 | 298 | 43 | 341 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15978 | yes | 7.64 | 0 |
| SoliSpirit-all | 8785 | yes | 3.19 | 0 |
| Epodonios-all | 7601 | yes | 3.53 | 0 |
| Surfboard-tg-mixed | 7138 | yes | 6.27 | 0 |
| DeltaKronecker-all | 6421 | yes | 5.2 | 0 |
| barry-far-vless | 5908 | yes | 0.92 | 0 |
| Surfboard-tg-vless | 5693 | yes | 4.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 2.27 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 1.48 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.22 | 0 |

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
| geo | 86 |
| speed | 35 |
| cn-block | 31 |
| 204 | 30 |
