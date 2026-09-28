# AutoNodes 每日报告

生成时间：2026-09-28 05:17:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 95256 |
| 去重后节点数 | 26812 |
| TCP 可达数 | 3000 |
| 真测通过数 | 371 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26812 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 39.6 |
| geo | 1.5 |
| probe | 302.4 |
| real_test | 441.0 |
| tcp | 44.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 48 | 28 | 20 | 58.3% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 194 | 177 | 17 | 91.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 3 | 2 | 1 | 66.7% |
| vless | 492 | 140 | 352 | 28.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 170 |
| speed:TimeoutError | 84 |
| geo:ClientOSError | 57 |
| speed:ClientOSError | 22 |
| 204:ProxyError | 20 |
| 204:ProxyConnectionError | 10 |
| 204:TimeoutError | 10 |
| cn-block:TimeoutError | 8 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 2 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5995 |
| ConnectionRefusedError | 950 |
| gaierror | 387 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 112 | 0.982 | 1437 |
| Surfboard-tg-mixed | 0.686 | observe | 107 | 0.607 | 6916 |
| ermaozi | 0.648 | observe | 39 | 0.641 | 347 |
| mheidari-all | 0.417 | observe | 482 | 0.336 | 22305 |
| DeltaKronecker-all | 0.407 | observe | 11 | 0.455 | 5466 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7506 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9195 |

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
| downweight | ermaozi-get_subscribe | 0.207 | 7 | 0.286 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.286 | 2 | 5 | 7 |
| mheidari-all | 0.336 | 162 | 320 | 482 |
| DeltaKronecker-all | 0.455 | 5 | 6 | 11 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.607 | 65 | 42 | 107 |
| ermaozi | 0.641 | 25 | 14 | 39 |
| Au1rxx-base64 | 0.982 | 110 | 2 | 112 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22305 | yes | 6.57 | 0 |
| SoliSpirit-all | 9195 | yes | 5.34 | 0 |
| Epodonios-all | 7506 | yes | 1.52 | 0 |
| Surfboard-tg-mixed | 6916 | yes | 5.01 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.88 | 0 |
| barry-far-vless | 5817 | yes | 3.06 | 0 |
| Surfboard-tg-vless | 5591 | yes | 4.13 | 0 |
| DeltaKronecker-all | 5466 | yes | 5.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 3.3 | 0 |
| mahdibland-V2RayAggregator | 4185 | yes | 3.23 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 229 |
| speed | 106 |
| 204 | 44 |
| cn-block | 13 |
