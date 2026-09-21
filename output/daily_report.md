# AutoNodes 每日报告

生成时间：2026-09-21 18:27:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 85428 |
| 去重后节点数 | 23571 |
| TCP 可达数 | 3000 |
| 真测通过数 | 417 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23571 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 23.5 |
| geo | 1.4 |
| probe | 209.1 |
| real_test | 209.7 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 37 | 14 | 23 | 37.8% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 114 | 107 | 7 | 93.9% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 21 | 11 | 10 | 52.4% |
| vless | 407 | 268 | 139 | 65.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 41 |
| geo:TimeoutError | 34 |
| 204:ProxyError | 26 |
| geo:ClientOSError | 25 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 17 |
| speed:TimeoutError | 13 |
| 204:ProxyConnectionError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5330 |
| ConnectionRefusedError | 822 |
| gaierror | 287 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.914 | prefer | 273 | 0.846 | 1766 |
| mheidari-all | 0.834 | prefer | 55 | 0.764 | 16282 |
| DeltaKronecker-all | 0.637 | observe | 208 | 0.558 | 6181 |
| Surfboard-tg-mixed | 0.622 | observe | 22 | 0.545 | 7273 |
| ermaozi | 0.533 | observe | 25 | 0.52 | 350 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 123 |
| Epodonios-all | 0.255 | observe | 0 | None | 7695 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.07 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.0 | 0 | 11 | 11 |
| ermaozi | 0.52 | 13 | 12 | 25 |
| Surfboard-tg-mixed | 0.545 | 12 | 10 | 22 |
| DeltaKronecker-all | 0.558 | 116 | 92 | 208 |
| mheidari-all | 0.764 | 42 | 13 | 55 |
| Au1rxx-base64 | 0.846 | 231 | 42 | 273 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16282 | yes | 5.43 | 0 |
| SoliSpirit-all | 9453 | yes | 4.74 | 0 |
| Epodonios-all | 7695 | yes | 5.74 | 0 |
| Surfboard-tg-mixed | 7273 | yes | 4.39 | 0 |
| DeltaKronecker-all | 6181 | yes | 5.94 | 0 |
| barry-far-vless | 6075 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 5859 | yes | 4.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 3.51 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 3.09 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 59 |
| speed | 55 |
| 204 | 49 |
| cn-block | 19 |
