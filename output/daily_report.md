# AutoNodes 每日报告

生成时间：2026-09-18 00:43:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 84592 |
| 去重后节点数 | 23112 |
| TCP 可达数 | 3000 |
| 真测通过数 | 643 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23112 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 79.8 |
| geo | 1.4 |
| probe | 422.2 |
| real_test | 622.3 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 34 | 24 | 10 | 70.6% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 175 | 167 | 8 | 95.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 9 | 7 | 2 | 77.8% |
| vless | 911 | 421 | 490 | 46.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 221 |
| speed:ClientOSError | 81 |
| geo:ClientOSError | 81 |
| speed:TimeoutError | 64 |
| 204:ProxyError | 20 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 13 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5189 |
| ConnectionRefusedError | 840 |
| gaierror | 361 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | prefer | 290 | 0.9 | 1671 |
| ermaozi | 0.742 | prefer | 31 | 0.742 | 357 |
| Surfboard-tg-mixed | 0.656 | observe | 229 | 0.576 | 7509 |
| mheidari-all | 0.535 | observe | 99 | 0.455 | 16000 |
| DeltaKronecker-all | 0.439 | observe | 497 | 0.358 | 5931 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4261 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5093 |
| Epodonios-all | 0.255 | observe | 0 | None | 7969 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| DeltaKronecker-all | 0.358 | 178 | 319 | 497 |
| mheidari-all | 0.455 | 45 | 54 | 99 |
| ermaozi-get_subscribe | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.576 | 132 | 97 | 229 |
| ermaozi | 0.742 | 23 | 8 | 31 |
| Au1rxx-base64 | 0.9 | 261 | 29 | 290 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16000 | yes | 4.72 | 0 |
| SoliSpirit-all | 8923 | yes | 5.05 | 0 |
| Epodonios-all | 7969 | yes | 5.08 | 0 |
| Surfboard-tg-mixed | 7509 | yes | 3.81 | 0 |
| barry-far-vless | 6183 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 5961 | yes | 4.3 | 0 |
| DeltaKronecker-all | 5931 | yes | 4.38 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 4261 | yes | 3.04 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.91 | 0 |

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
| geo | 304 |
| speed | 146 |
| 204 | 31 |
| cn-block | 31 |
