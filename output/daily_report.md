# AutoNodes 每日报告

生成时间：2026-10-08 05:16:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 99184 |
| 去重后节点数 | 27677 |
| TCP 可达数 | 3000 |
| 真测通过数 | 463 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27677 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.9 |
| generate | 93.1 |
| geo | 1.5 |
| probe | 356.3 |
| real_test | 430.9 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 0 | 6 | 0.0% |
| http | 60 | 22 | 38 | 36.7% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 162 | 157 | 5 | 96.9% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 87 | 77 | 10 | 88.5% |
| vless | 520 | 191 | 329 | 36.7% |
| vmess | 2 | 0 | 2 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 162 |
| speed:TimeoutError | 56 |
| 204:ProxyError | 47 |
| geo:ClientOSError | 41 |
| speed:ClientOSError | 26 |
| 204:ProxyConnectionError | 20 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 11 |
| cn-block:ClientOSError | 9 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6591 |
| ConnectionRefusedError | 1009 |
| gaierror | 402 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | prefer | 327 | 0.914 | 1781 |
| Surfboard-tg-mixed | 0.866 | prefer | 40 | 0.8 | 7193 |
| ermaozi-get_subscribe | 0.399 | observe | 30 | 0.367 | 592 |
| mheidari-all | 0.348 | observe | 404 | 0.267 | 23407 |
| ermaozi | 0.344 | observe | 36 | 0.306 | 715 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7663 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9553 |
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
| downweight | DeltaKronecker-all | 0.222 | 17 | 0.118 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.118 | 2 | 15 | 17 |
| mheidari-all | 0.267 | 108 | 296 | 404 |
| ermaozi | 0.306 | 11 | 25 | 36 |
| ermaozi-get_subscribe | 0.367 | 11 | 19 | 30 |
| Surfboard-tg-mixed | 0.8 | 32 | 8 | 40 |
| Au1rxx-base64 | 0.914 | 299 | 28 | 327 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23407 | yes | 6.89 | 0 |
| SoliSpirit-all | 9553 | yes | 4.39 | 0 |
| Epodonios-all | 7663 | yes | 5.78 | 0 |
| Surfboard-tg-mixed | 7193 | yes | 4.91 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.76 | 0 |
| barry-far-vless | 5963 | yes | 2.74 | 0 |
| Surfboard-tg-vless | 5725 | yes | 4.33 | 0 |
| DeltaKronecker-all | 5344 | yes | 6.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 5138 | yes | 2.31 | 0 |
| mahdibland-V2RayAggregator | 4431 | yes | 3.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |
| anytls | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 204 |
| speed | 84 |
| 204 | 79 |
| cn-block | 26 |
