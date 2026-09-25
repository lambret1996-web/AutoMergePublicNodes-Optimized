# AutoNodes 每日报告

生成时间：2026-09-25 11:48:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 96970 |
| 去重后节点数 | 26329 |
| TCP 可达数 | 3000 |
| 真测通过数 | 375 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26329 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 97.7 |
| geo | 1.5 |
| probe | 228.4 |
| real_test | 162.3 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 46 | 32 | 14 | 69.6% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 165 | 147 | 18 | 89.1% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 16 | 9 | 7 | 56.2% |
| vless | 218 | 164 | 54 | 75.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 24 |
| cn-block:TimeoutError | 24 |
| 204:TimeoutError | 17 |
| cn-block:ClientOSError | 11 |
| speed:TimeoutError | 5 |
| geo:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| speed:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6098 |
| ConnectionRefusedError | 965 |
| gaierror | 385 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.961 | prefer | 238 | 0.899 | 1624 |
| mheidari-all | 0.817 | prefer | 74 | 0.743 | 22444 |
| Surfboard-tg-mixed | 0.753 | prefer | 102 | 0.676 | 7280 |
| ermaozi | 0.701 | prefer | 46 | 0.696 | 338 |
| DeltaKronecker-all | 0.361 | observe | 10 | 0.4 | 5452 |
| ermaozi-get_subscribe | 0.269 | observe | 1 | 1.0 | 359 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7869 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9069 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.4 | 4 | 6 | 10 |
| Surfboard-tg-mixed | 0.676 | 69 | 33 | 102 |
| ermaozi | 0.696 | 32 | 14 | 46 |
| mheidari-all | 0.743 | 55 | 19 | 74 |
| Au1rxx-base64 | 0.899 | 214 | 24 | 238 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22444 | yes | 4.56 | 0 |
| SoliSpirit-all | 9069 | yes | 3.24 | 0 |
| Epodonios-all | 7869 | yes | 2.31 | 0 |
| Surfboard-tg-mixed | 7280 | yes | 3.46 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.1 | 0 |
| barry-far-vless | 6140 | yes | 1.53 | 0 |
| Surfboard-tg-vless | 5801 | yes | 4.07 | 0 |
| DeltaKronecker-all | 5452 | yes | 3.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 1.38 | 0 |
| mahdibland-V2RayAggregator | 4324 | yes | 1.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 44 |
| cn-block | 38 |
| geo | 9 |
| speed | 8 |
