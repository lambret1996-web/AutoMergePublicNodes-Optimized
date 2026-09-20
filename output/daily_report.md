# AutoNodes 每日报告

生成时间：2026-09-20 18:28:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83333 |
| 去重后节点数 | 23378 |
| TCP 可达数 | 3000 |
| 真测通过数 | 465 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23378 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 83.8 |
| geo | 1.5 |
| probe | 259.6 |
| real_test | 204.5 |
| tcp | 38.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 31 | 26 | 5 | 83.9% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 166 | 146 | 20 | 88.0% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 18 | 6 | 12 | 33.3% |
| vless | 390 | 266 | 124 | 68.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 40 |
| geo:ClientOSError | 31 |
| geo:TimeoutError | 20 |
| cn-block:TimeoutError | 19 |
| cn-block:ClientOSError | 15 |
| 204:ProxyError | 12 |
| speed:TimeoutError | 9 |
| cn-block:ProxyError | 6 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5272 |
| ConnectionRefusedError | 795 |
| gaierror | 353 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.923 | prefer | 286 | 0.864 | 1556 |
| ermaozi | 0.87 | prefer | 26 | 0.885 | 314 |
| DeltaKronecker-all | 0.777 | prefer | 31 | 0.71 | 6092 |
| mheidari-all | 0.775 | prefer | 57 | 0.702 | 15889 |
| Surfboard-tg-mixed | 0.682 | observe | 214 | 0.603 | 7161 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4315 |
| tg-oneclickvpnkeys | 0.314 | observe | 2 | 1.0 | 59 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7593 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-ScrapeCategorize-Vless | 0.148 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 6 | 6 |
| Surfboard-tg-mixed | 0.603 | 129 | 85 | 214 |
| mheidari-all | 0.702 | 40 | 17 | 57 |
| DeltaKronecker-all | 0.71 | 22 | 9 | 31 |
| Au1rxx-base64 | 0.864 | 247 | 39 | 286 |
| ermaozi | 0.885 | 23 | 3 | 26 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15889 | yes | 4.5 | 0 |
| SoliSpirit-all | 9013 | yes | 3.3 | 0 |
| Epodonios-all | 7593 | yes | 4.77 | 0 |
| Surfboard-tg-mixed | 7161 | yes | 3.91 | 0 |
| DeltaKronecker-all | 6092 | yes | 5.07 | 0 |
| barry-far-vless | 5918 | yes | 1.69 | 0 |
| Surfboard-tg-vless | 5710 | yes | 4.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 1.49 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 0.52 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 55 |
| geo | 53 |
| cn-block | 40 |
| speed | 16 |
