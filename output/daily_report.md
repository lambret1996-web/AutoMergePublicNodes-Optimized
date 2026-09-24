# AutoNodes 每日报告

生成时间：2026-09-24 17:08:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97082 |
| 去重后节点数 | 26416 |
| TCP 可达数 | 3000 |
| 真测通过数 | 396 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26416 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 78.3 |
| geo | 1.5 |
| probe | 218.6 |
| real_test | 163.2 |
| tcp | 43.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 38 | 26 | 12 | 68.4% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 162 | 146 | 16 | 90.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 21 | 18 | 3 | 85.7% |
| vless | 233 | 185 | 48 | 79.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 17 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 13 |
| 204:ClientOSError | 6 |
| geo:TimeoutError | 6 |
| speed:TimeoutError | 4 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5872 |
| ConnectionRefusedError | 976 |
| gaierror | 316 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 257 | 0.922 | 1697 |
| mheidari-all | 0.826 | prefer | 65 | 0.754 | 22258 |
| Surfboard-tg-mixed | 0.815 | prefer | 111 | 0.739 | 7421 |
| ermaozi | 0.679 | observe | 34 | 0.676 | 298 |
| tg-oneclickvpnkeys | 0.315 | observe | 2 | 1.0 | 85 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 5845 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5307 |
| Epodonios-all | 0.255 | observe | 0 | None | 7498 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9120 |

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
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| ermaozi-get_subscribe | 0.5 | 2 | 2 | 4 |
| ermaozi | 0.676 | 23 | 11 | 34 |
| Surfboard-tg-mixed | 0.739 | 82 | 29 | 111 |
| mheidari-all | 0.754 | 49 | 16 | 65 |
| Au1rxx-base64 | 0.922 | 237 | 20 | 257 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22258 | yes | 5.85 | 0 |
| SoliSpirit-all | 9120 | yes | 4.33 | 0 |
| Epodonios-all | 7498 | yes | 3.01 | 0 |
| Surfboard-tg-mixed | 7421 | yes | 4.68 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.55 | 0 |
| Surfboard-tg-vless | 5991 | yes | 4.39 | 0 |
| barry-far-vless | 5901 | yes | 0.94 | 0 |
| DeltaKronecker-all | 5845 | yes | 5.16 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 2.68 | 0 |
| mahdibland-V2RayAggregator | 4305 | yes | 2.79 | 0 |

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
| 204 | 40 |
| cn-block | 27 |
| speed | 7 |
| geo | 7 |
