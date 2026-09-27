# AutoNodes 每日报告

生成时间：2026-09-27 12:01:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 95691 |
| 去重后节点数 | 26593 |
| TCP 可达数 | 3000 |
| 真测通过数 | 417 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26593 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 74.4 |
| geo | 1.5 |
| probe | 238.4 |
| real_test | 202.5 |
| tcp | 43.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 71 | 48 | 23 | 67.6% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 178 | 152 | 26 | 85.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 29 | 14 | 15 | 48.3% |
| vless | 258 | 181 | 77 | 70.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 27 |
| 204:ProxyError | 26 |
| 204:TimeoutError | 23 |
| geo:TimeoutError | 21 |
| cn-block:ClientOSError | 12 |
| speed:TimeoutError | 12 |
| speed:ClientOSError | 8 |
| geo:ClientOSError | 6 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6284 |
| ConnectionRefusedError | 942 |
| gaierror | 344 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.901 | prefer | 281 | 0.84 | 1589 |
| ermaozi | 0.73 | prefer | 58 | 0.724 | 338 |
| Surfboard-tg-mixed | 0.72 | prefer | 109 | 0.642 | 7025 |
| mheidari-all | 0.709 | prefer | 87 | 0.632 | 22397 |
| ermaozi-get_subscribe | 0.417 | observe | 14 | 0.5 | 361 |
| DeltaKronecker-all | 0.385 | observe | 8 | 0.5 | 5466 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 4 | 4 | 8 |
| ermaozi-get_subscribe | 0.5 | 7 | 7 | 14 |
| mheidari-all | 0.632 | 55 | 32 | 87 |
| Surfboard-tg-mixed | 0.642 | 70 | 39 | 109 |
| ermaozi | 0.724 | 42 | 16 | 58 |
| Au1rxx-base64 | 0.84 | 236 | 45 | 281 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22397 | yes | 3.52 | 0 |
| SoliSpirit-all | 8971 | yes | 2.45 | 0 |
| Epodonios-all | 7510 | yes | 1.74 | 0 |
| Surfboard-tg-mixed | 7025 | yes | 2.55 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.42 | 0 |
| barry-far-vless | 5862 | yes | 1.86 | 0 |
| Surfboard-tg-vless | 5637 | yes | 2.71 | 0 |
| DeltaKronecker-all | 5466 | yes | 2.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.34 | 0 |
| mahdibland-V2RayAggregator | 4277 | yes | 0.9 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 55 |
| cn-block | 42 |
| geo | 27 |
| speed | 20 |
