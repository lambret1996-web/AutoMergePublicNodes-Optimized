# AutoNodes 每日报告

生成时间：2026-09-25 04:52:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97833 |
| 去重后节点数 | 26571 |
| TCP 可达数 | 3000 |
| 真测通过数 | 457 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26571 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 89.3 |
| geo | 1.4 |
| probe | 348.7 |
| real_test | 438.1 |
| tcp | 44.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 30 | 20 | 10 | 66.7% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 176 | 163 | 13 | 92.6% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 11 | 11 | 0 | 100.0% |
| vless | 663 | 237 | 426 | 35.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 160 |
| speed:TimeoutError | 68 |
| cn-block:ClientOSError | 63 |
| geo:ClientOSError | 47 |
| 204:ProxyError | 36 |
| 204:TimeoutError | 30 |
| speed:ClientOSError | 22 |
| cn-block:TimeoutError | 22 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6432 |
| ConnectionRefusedError | 956 |
| gaierror | 288 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | prefer | 267 | 0.899 | 1701 |
| Surfboard-tg-mixed | 0.749 | prefer | 164 | 0.671 | 7399 |
| ermaozi | 0.643 | observe | 25 | 0.64 | 338 |
| ermaozi-get_subscribe | 0.38 | observe | 5 | 0.8 | 359 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4405 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 5845 |
| mheidari-all | 0.272 | observe | 440 | 0.191 | 22554 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5307 |
| Epodonios-all | 0.255 | observe | 0 | None | 7876 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.191 | 84 | 356 | 440 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| ermaozi | 0.64 | 16 | 9 | 25 |
| Surfboard-tg-mixed | 0.671 | 110 | 54 | 164 |
| ermaozi-get_subscribe | 0.8 | 4 | 1 | 5 |
| Au1rxx-base64 | 0.899 | 240 | 27 | 267 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22554 | yes | 3.38 | 0 |
| SoliSpirit-all | 9018 | yes | 1.87 | 0 |
| Epodonios-all | 7876 | yes | 0.17 | 0 |
| Surfboard-tg-mixed | 7399 | yes | 2.29 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.19 | 0 |
| barry-far-vless | 6091 | yes | 1.49 | 0 |
| Surfboard-tg-vless | 5862 | yes | 2.98 | 0 |
| DeltaKronecker-all | 5845 | yes | 3.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 1.38 | 0 |
| mahdibland-V2RayAggregator | 4405 | yes | 1.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 207 |
| speed | 91 |
| cn-block | 88 |
| 204 | 66 |
