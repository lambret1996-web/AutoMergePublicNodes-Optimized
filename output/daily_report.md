# AutoNodes 每日报告

生成时间：2026-10-07 05:05:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 97137 |
| 去重后节点数 | 27057 |
| TCP 可达数 | 3000 |
| 真测通过数 | 487 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27057 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 38.0 |
| geo | 1.5 |
| probe | 292.8 |
| real_test | 486.3 |
| tcp | 45.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 0 | 5 | 0.0% |
| http | 41 | 20 | 21 | 48.8% |
| hysteria2 | 28 | 27 | 1 | 96.4% |
| shadowsocks | 169 | 153 | 16 | 90.5% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 120 | 96 | 24 | 80.0% |
| vless | 515 | 187 | 328 | 36.3% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 170 |
| speed:TimeoutError | 84 |
| 204:ProxyError | 32 |
| geo:ClientOSError | 31 |
| 204:TimeoutError | 21 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 18 |
| 204:ProxyConnectionError | 8 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6084 |
| ConnectionRefusedError | 981 |
| gaierror | 434 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 315 | 0.895 | 1811 |
| Surfboard-tg-mixed | 0.705 | prefer | 62 | 0.629 | 7006 |
| ermaozi | 0.517 | observe | 41 | 0.488 | 726 |
| mheidari-all | 0.399 | observe | 450 | 0.318 | 22990 |
| DeltaKronecker-all | 0.305 | observe | 10 | 0.3 | 4889 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7476 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9203 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5583 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.097 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.0 | 0 | 5 | 5 |
| DeltaKronecker-all | 0.3 | 3 | 7 | 10 |
| mheidari-all | 0.318 | 143 | 307 | 450 |
| ermaozi | 0.488 | 20 | 21 | 41 |
| Surfboard-tg-mixed | 0.629 | 39 | 23 | 62 |
| Au1rxx-base64 | 0.895 | 282 | 33 | 315 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22990 | yes | 6.76 | 0 |
| SoliSpirit-all | 9203 | yes | 4.82 | 0 |
| Epodonios-all | 7476 | yes | 3.92 | 0 |
| Surfboard-tg-mixed | 7006 | yes | 4.47 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.94 | 0 |
| barry-far-vless | 5837 | yes | 3.5 | 0 |
| Surfboard-tg-vless | 5583 | yes | 7.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 2.98 | 0 |
| DeltaKronecker-all | 4889 | yes | 5.68 | 0 |
| mahdibland-V2RayAggregator | 4373 | yes | 3.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 202 |
| speed | 104 |
| 204 | 66 |
| cn-block | 27 |
