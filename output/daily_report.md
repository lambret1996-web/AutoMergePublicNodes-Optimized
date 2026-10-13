# AutoNodes 每日报告

生成时间：2026-10-13 06:11:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 100384 |
| 去重后节点数 | 27896 |
| TCP 可达数 | 3000 |
| 真测通过数 | 441 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27896 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 77.4 |
| geo | 1.5 |
| probe | 354.1 |
| real_test | 575.2 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 0 | 2 | 0.0% |
| http | 40 | 20 | 20 | 50.0% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 138 | 121 | 17 | 87.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 98 | 95 | 3 | 96.9% |
| vless | 497 | 186 | 311 | 37.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 155 |
| speed:TimeoutError | 60 |
| geo:ClientOSError | 27 |
| 204:ProxyError | 26 |
| cn-block:TimeoutError | 24 |
| speed:ClientOSError | 21 |
| 204:TimeoutError | 20 |
| 204:ProxyConnectionError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| cn-block:ClientOSError | 4 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6281 |
| ConnectionRefusedError | 1066 |
| gaierror | 444 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | prefer | 329 | 0.906 | 1761 |
| ermaozi | 0.541 | observe | 41 | 0.512 | 723 |
| Surfboard-tg-mixed | 0.418 | observe | 10 | 0.5 | 7206 |
| mheidari-all | 0.375 | observe | 385 | 0.294 | 24063 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5028 |
| Epodonios-all | 0.255 | observe | 0 | None | 7717 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9931 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5725 |

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
| downweight | DeltaKronecker-all | 0.223 | 26 | 0.115 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.115 | 3 | 23 | 26 |
| mheidari-all | 0.294 | 113 | 272 | 385 |
| Surfboard-tg-mixed | 0.5 | 5 | 5 | 10 |
| ermaozi | 0.512 | 21 | 20 | 41 |
| Au1rxx-base64 | 0.906 | 298 | 31 | 329 |
| ninja-vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24063 | yes | 7.07 | 0 |
| SoliSpirit-all | 9931 | yes | 3.48 | 0 |
| Epodonios-all | 7717 | yes | 6.36 | 0 |
| Surfboard-tg-mixed | 7206 | yes | 4.88 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.31 | 0 |
| barry-far-vless | 5926 | yes | 2.84 | 0 |
| Surfboard-tg-vless | 5725 | yes | 4.43 | 0 |
| DeltaKronecker-all | 5701 | yes | 7.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 5028 | yes | 2.41 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 0.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 183 |
| speed | 81 |
| 204 | 58 |
| cn-block | 32 |
