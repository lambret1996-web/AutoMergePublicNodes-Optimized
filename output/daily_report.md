# AutoNodes 每日报告

生成时间：2026-10-15 16:41:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 100051 |
| 去重后节点数 | 27882 |
| TCP 可达数 | 3000 |
| 真测通过数 | 368 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27882 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 85.3 |
| geo | 1.5 |
| probe | 270.3 |
| real_test | 255.5 |
| tcp | 48.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 68 | 18 | 50 | 26.5% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 128 | 117 | 11 | 91.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 32 | 32 | 0 | 100.0% |
| vless | 272 | 185 | 87 | 68.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 38 |
| 204:TimeoutError | 27 |
| 204:ProxyConnectionError | 21 |
| speed:ClientOSError | 16 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 8 |
| geo:ClientOSError | 7 |
| geo:TimeoutError | 7 |
| speed:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6675 |
| ConnectionRefusedError | 1046 |
| gaierror | 286 |
| OSError | 240 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.87 | prefer | 417 | 0.801 | 1767 |
| mheidari-all | 0.555 | observe | 17 | 0.529 | 24080 |
| Surfboard-tg-mixed | 0.352 | observe | 6 | 0.5 | 7281 |
| ermaozi | 0.298 | observe | 68 | 0.265 | 659 |
| ermaozi-get_subscribe | 0.289 | observe | 3 | 0.667 | 519 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Epodonios-all | 0.255 | observe | 0 | None | 7794 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10074 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.143 | 1 | 6 | 7 |
| ermaozi | 0.265 | 18 | 50 | 68 |
| Surfboard-tg-mixed | 0.5 | 3 | 3 | 6 |
| mheidari-all | 0.529 | 9 | 8 | 17 |
| ermaozi-get_subscribe | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.801 | 334 | 83 | 417 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24080 | yes | 6.37 | 0 |
| SoliSpirit-all | 10074 | yes | 3.8 | 0 |
| Epodonios-all | 7794 | yes | 5.68 | 0 |
| Surfboard-tg-mixed | 7281 | yes | 4.68 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.27 | 0 |
| barry-far-vless | 5961 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 5707 | yes | 3.98 | 0 |
| DeltaKronecker-all | 5147 | yes | 9.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 1.1 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 0.73 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 90 |
| cn-block | 23 |
| speed | 23 |
| geo | 16 |
