# AutoNodes 每日报告

生成时间：2026-10-06 05:38:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 98379 |
| 去重后节点数 | 27433 |
| TCP 可达数 | 3000 |
| 真测通过数 | 548 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27433 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 76.4 |
| geo | 1.5 |
| probe | 362.0 |
| real_test | 462.2 |
| tcp | 47.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 1 | 3 | 25.0% |
| http | 54 | 34 | 20 | 63.0% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 170 | 157 | 13 | 92.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 96 | 87 | 9 | 90.6% |
| vless | 564 | 248 | 316 | 44.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 180 |
| speed:TimeoutError | 71 |
| geo:ClientOSError | 33 |
| 204:ProxyError | 25 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 10 |
| speed:ClientOSError | 8 |
| cn-block:ClientOSError | 5 |
| 204:ProxyConnectionError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6593 |
| ConnectionRefusedError | 1025 |
| gaierror | 359 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.998 | prefer | 362 | 0.928 | 1801 |
| Surfboard-tg-mixed | 0.82 | prefer | 48 | 0.75 | 7083 |
| ermaozi | 0.653 | observe | 54 | 0.63 | 691 |
| mheidari-all | 0.409 | observe | 421 | 0.328 | 23039 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| Epodonios-all | 0.255 | observe | 0 | None | 7631 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9601 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5600 |

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
| downweight | DeltaKronecker-all | 0.179 | 15 | 0.067 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.067 | 1 | 14 | 15 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| mheidari-all | 0.328 | 138 | 283 | 421 |
| ermaozi | 0.63 | 34 | 20 | 54 |
| Surfboard-tg-mixed | 0.75 | 36 | 12 | 48 |
| Au1rxx-base64 | 0.928 | 336 | 26 | 362 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23039 | yes | 6.71 | 0 |
| SoliSpirit-all | 9601 | yes | 2.52 | 0 |
| Epodonios-all | 7631 | yes | 3.97 | 0 |
| Surfboard-tg-mixed | 7083 | yes | 5.6 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.46 | 0 |
| barry-far-vless | 5876 | yes | 1.7 | 0 |
| Surfboard-tg-vless | 5600 | yes | 5.37 | 0 |
| DeltaKronecker-all | 5300 | yes | 6.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 5111 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 4375 | yes | 3.56 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 213 |
| speed | 79 |
| 204 | 43 |
| cn-block | 27 |
