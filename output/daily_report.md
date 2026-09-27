# AutoNodes 每日报告

生成时间：2026-09-27 16:59:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96135 |
| 去重后节点数 | 26661 |
| TCP 可达数 | 3000 |
| 真测通过数 | 344 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26661 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 91.2 |
| geo | 1.5 |
| probe | 235.7 |
| real_test | 186.0 |
| tcp | 44.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 37 | 18 | 19 | 48.6% |
| hysteria2 | 24 | 21 | 3 | 87.5% |
| shadowsocks | 163 | 148 | 15 | 90.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 7 | 6 | 1 | 85.7% |
| vless | 224 | 148 | 76 | 66.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 23 |
| geo:TimeoutError | 22 |
| 204:TimeoutError | 20 |
| 204:ProxyError | 15 |
| speed:TimeoutError | 13 |
| 204:ProxyConnectionError | 9 |
| speed:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 1 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5874 |
| ConnectionRefusedError | 975 |
| gaierror | 363 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.895 | prefer | 52 | 0.827 | 22413 |
| Au1rxx-base64 | 0.838 | prefer | 307 | 0.775 | 1601 |
| Surfboard-tg-mixed | 0.794 | prefer | 54 | 0.722 | 7109 |
| ermaozi | 0.57 | observe | 32 | 0.562 | 289 |
| DeltaKronecker-all | 0.465 | observe | 7 | 0.714 | 5466 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7600 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9194 |

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
| downweight | ermaozi-get_subscribe | 0.085 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 5 | 5 |
| ermaozi | 0.562 | 18 | 14 | 32 |
| DeltaKronecker-all | 0.714 | 5 | 2 | 7 |
| Surfboard-tg-mixed | 0.722 | 39 | 15 | 54 |
| Au1rxx-base64 | 0.775 | 238 | 69 | 307 |
| mheidari-all | 0.827 | 43 | 9 | 52 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22413 | yes | 6.45 | 0 |
| SoliSpirit-all | 9194 | yes | 4.95 | 0 |
| Epodonios-all | 7600 | yes | 3.29 | 0 |
| Surfboard-tg-mixed | 7109 | yes | 4.51 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.18 | 0 |
| barry-far-vless | 5938 | yes | 1.29 | 0 |
| Surfboard-tg-vless | 5703 | yes | 4.07 | 0 |
| DeltaKronecker-all | 5466 | yes | 5.71 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 3.1 | 0 |
| mahdibland-V2RayAggregator | 4277 | yes | 3.06 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 44 |
| cn-block | 29 |
| geo | 24 |
| speed | 18 |
