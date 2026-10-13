# AutoNodes 每日报告

生成时间：2026-10-13 19:14:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 99089 |
| 去重后节点数 | 27412 |
| TCP 可达数 | 3000 |
| 真测通过数 | 428 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27412 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 78.5 |
| geo | 1.5 |
| probe | 346.5 |
| real_test | 325.3 |
| tcp | 48.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 4 | 0 | 100.0% |
| http | 26 | 14 | 12 | 53.8% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 143 | 126 | 17 | 88.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 105 | 90 | 15 | 85.7% |
| vless | 228 | 182 | 46 | 79.8% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 20 |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 8 |
| speed:ClientOSError | 7 |
| geo:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7043 |
| ConnectionRefusedError | 1028 |
| gaierror | 274 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | prefer | 340 | 0.912 | 1802 |
| mheidari-all | 0.88 | prefer | 43 | 0.814 | 24075 |
| zhangkai | 0.71 | prefer | 14 | 0.929 | 144 |
| Surfboard-tg-mixed | 0.683 | observe | 76 | 0.605 | 7201 |
| DeltaKronecker-all | 0.674 | observe | 30 | 0.6 | 5076 |
| ermaozi-get_subscribe | 0.306 | observe | 17 | 0.294 | 534 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5086 |
| Epodonios-all | 0.255 | observe | 0 | None | 7712 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| ermaozi-get_subscribe | 0.294 | 5 | 12 | 17 |
| DeltaKronecker-all | 0.6 | 18 | 12 | 30 |
| Surfboard-tg-mixed | 0.605 | 46 | 30 | 76 |
| mheidari-all | 0.814 | 35 | 8 | 43 |
| Au1rxx-base64 | 0.912 | 310 | 30 | 340 |
| zhangkai | 0.929 | 13 | 1 | 14 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24075 | yes | 5.05 | 0 |
| SoliSpirit-all | 9906 | yes | 3.46 | 0 |
| Epodonios-all | 7712 | yes | 4.25 | 0 |
| Surfboard-tg-mixed | 7201 | yes | 4.49 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.07 | 0 |
| barry-far-vless | 5972 | yes | 2.39 | 0 |
| Surfboard-tg-vless | 5723 | yes | 3.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 5086 | yes | 2.32 | 0 |
| DeltaKronecker-all | 5076 | yes | 4.71 | 0 |
| mahdibland-V2RayAggregator | 4312 | yes | 0.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| cn-block | 25 |
| geo | 16 |
| speed | 12 |
