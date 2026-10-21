# AutoNodes 每日报告

生成时间：2026-10-21 03:53:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 95344 |
| 去重后节点数 | 26608 |
| TCP 可达数 | 3000 |
| 真测通过数 | 378 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26608 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 82.7 |
| geo | 1.5 |
| probe | 244.5 |
| real_test | 259.4 |
| tcp | 44.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 58 | 32 | 26 | 55.2% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 127 | 118 | 9 | 92.9% |
| socks | 4 | 4 | 0 | 100.0% |
| trojan | 37 | 35 | 2 | 94.6% |
| vless | 317 | 174 | 143 | 54.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 60 |
| 204:ProxyError | 29 |
| geo:ClientOSError | 29 |
| speed:ClientOSError | 23 |
| speed:TimeoutError | 13 |
| 204:TimeoutError | 8 |
| cn-block:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6527 |
| ConnectionRefusedError | 1034 |
| gaierror | 266 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.952 | prefer | 254 | 0.898 | 1433 |
| zhangkai | 0.592 | observe | 20 | 0.6 | 31 |
| DeltaKronecker-all | 0.569 | observe | 43 | 0.488 | 3519 |
| ermaozi-get_subscribe | 0.557 | observe | 39 | 0.538 | 516 |
| mheidari-all | 0.536 | observe | 193 | 0.456 | 23653 |
| Surfboard-tg-mixed | 0.529 | observe | 7 | 0.857 | 7115 |
| SoliSpirit-all | 0.335 | observe | 1 | 1.0 | 10016 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| Epodonios-all | 0.255 | observe | 0 | None | 7598 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.456 | 88 | 105 | 193 |
| DeltaKronecker-all | 0.488 | 21 | 22 | 43 |
| ermaozi-get_subscribe | 0.538 | 21 | 18 | 39 |
| zhangkai | 0.6 | 12 | 8 | 20 |
| Surfboard-tg-mixed | 0.857 | 6 | 1 | 7 |
| Au1rxx-base64 | 0.898 | 228 | 26 | 254 |
| SoliSpirit-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23653 | yes | 6.33 | 0 |
| SoliSpirit-all | 10016 | yes | 3.98 | 0 |
| Epodonios-all | 7598 | yes | 6.52 | 0 |
| Surfboard-tg-mixed | 7115 | yes | 3.66 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.38 | 0 |
| barry-far-vless | 5764 | yes | 3.58 | 0 |
| Surfboard-tg-vless | 5552 | yes | 4.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 3.14 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 2.0 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.91 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 89 |
| 204 | 42 |
| speed | 36 |
| cn-block | 13 |
