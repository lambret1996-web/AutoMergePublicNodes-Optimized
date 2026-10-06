# AutoNodes 每日报告

生成时间：2026-10-06 18:13:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97513 |
| 去重后节点数 | 27042 |
| TCP 可达数 | 3000 |
| 真测通过数 | 448 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27042 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 80.4 |
| geo | 1.3 |
| probe | 285.2 |
| real_test | 191.4 |
| tcp | 45.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 2 | 4 | 33.3% |
| http | 79 | 40 | 39 | 50.6% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 140 | 128 | 12 | 91.4% |
| socks | 7 | 2 | 5 | 28.6% |
| trojan | 96 | 86 | 10 | 89.6% |
| vless | 230 | 171 | 59 | 74.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 49 |
| 204:TimeoutError | 26 |
| cn-block:TimeoutError | 22 |
| speed:ClientOSError | 8 |
| speed:TimeoutError | 6 |
| geo:ClientOSError | 6 |
| cn-block:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6232 |
| ConnectionRefusedError | 1030 |
| gaierror | 472 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | prefer | 309 | 0.893 | 1828 |
| mheidari-all | 0.864 | prefer | 49 | 0.796 | 23142 |
| Surfboard-tg-mixed | 0.772 | prefer | 128 | 0.695 | 7117 |
| ermaozi | 0.528 | observe | 80 | 0.5 | 708 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 4889 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7535 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9111 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5711 |

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
| downweight | ermaozi-get_subscribe | 0.228 | 6 | 0.333 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.333 | 2 | 4 | 6 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| ermaozi | 0.5 | 40 | 40 | 80 |
| Surfboard-tg-mixed | 0.695 | 89 | 39 | 128 |
| mheidari-all | 0.796 | 39 | 10 | 49 |
| Au1rxx-base64 | 0.893 | 276 | 33 | 309 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23142 | yes | 6.43 | 0 |
| SoliSpirit-all | 9111 | yes | 3.75 | 0 |
| Epodonios-all | 7535 | yes | 7.02 | 0 |
| Surfboard-tg-mixed | 7117 | yes | 4.03 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.29 | 0 |
| barry-far-vless | 5822 | yes | 1.28 | 0 |
| Surfboard-tg-vless | 5711 | yes | 4.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 0.76 | 0 |
| DeltaKronecker-all | 4889 | yes | 6.53 | 0 |
| mahdibland-V2RayAggregator | 4373 | yes | 3.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 77 |
| cn-block | 28 |
| speed | 14 |
| geo | 11 |
