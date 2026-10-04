# AutoNodes 每日报告

生成时间：2026-10-04 05:01:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 99156 |
| 去重后节点数 | 27380 |
| TCP 可达数 | 3000 |
| 真测通过数 | 469 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27380 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 75.6 |
| geo | 1.5 |
| probe | 286.1 |
| real_test | 403.4 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 170 | 153 | 17 | 90.0% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 64 | 59 | 5 | 92.2% |
| vless | 494 | 221 | 273 | 44.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 150 |
| speed:TimeoutError | 63 |
| geo:ClientOSError | 27 |
| 204:TimeoutError | 19 |
| cn-block:ClientOSError | 11 |
| cn-block:TimeoutError | 10 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6676 |
| ConnectionRefusedError | 1137 |
| gaierror | 406 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | prefer | 293 | 0.911 | 1797 |
| ermaozi | 0.949 | prefer | 24 | 0.958 | 646 |
| Surfboard-tg-mixed | 0.849 | prefer | 154 | 0.773 | 7318 |
| ermaozi-get_subscribe | 0.331 | observe | 2 | 1.0 | 505 |
| mheidari-all | 0.291 | observe | 277 | 0.209 | 23371 |
| Epodonios-all | 0.255 | observe | 0 | None | 7797 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9371 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5909 |
| barry-far-vless | 0.255 | observe | 0 | None | 6122 |

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
| downweight | DeltaKronecker-all | 0.134 | 11 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.0 | 0 | 11 | 11 |
| mheidari-all | 0.209 | 58 | 219 | 277 |
| Surfboard-tg-mixed | 0.773 | 119 | 35 | 154 |
| Au1rxx-base64 | 0.911 | 267 | 26 | 293 |
| ermaozi | 0.958 | 23 | 1 | 24 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23371 | yes | 6.63 | 0 |
| SoliSpirit-all | 9371 | yes | 2.17 | 0 |
| Epodonios-all | 7797 | yes | 3.81 | 0 |
| Surfboard-tg-mixed | 7318 | yes | 5.69 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.52 | 0 |
| barry-far-vless | 6122 | yes | 0.77 | 0 |
| Surfboard-tg-vless | 5909 | yes | 5.91 | 0 |
| DeltaKronecker-all | 5207 | yes | 6.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 1.75 | 0 |
| mahdibland-V2RayAggregator | 4285 | yes | 3.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 177 |
| speed | 72 |
| 204 | 25 |
| cn-block | 22 |
