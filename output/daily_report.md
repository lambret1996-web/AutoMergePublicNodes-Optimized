# AutoNodes 每日报告

生成时间：2026-10-22 03:54:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96952 |
| 去重后节点数 | 27034 |
| TCP 可达数 | 3000 |
| 真测通过数 | 418 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27034 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 16.2 |
| generate | 89.4 |
| geo | 1.7 |
| probe | 230.1 |
| real_test | 304.8 |
| tcp | 44.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 51 | 22 | 29 | 43.1% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 142 | 137 | 5 | 96.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 48 | 46 | 2 | 95.8% |
| vless | 346 | 197 | 149 | 56.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 69 |
| speed:ClientOSError | 25 |
| geo:ClientOSError | 21 |
| 204:ProxyError | 20 |
| speed:TimeoutError | 16 |
| cn-block:TimeoutError | 13 |
| 204:ProxyConnectionError | 8 |
| 204:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6664 |
| ConnectionRefusedError | 1042 |
| OSError | 237 |
| gaierror | 206 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.942 | prefer | 292 | 0.88 | 1599 |
| Surfboard-tg-mixed | 0.887 | prefer | 17 | 0.941 | 7097 |
| mheidari-all | 0.609 | observe | 221 | 0.529 | 24252 |
| zhangkai | 0.609 | observe | 18 | 0.667 | 31 |
| DeltaKronecker-all | 0.384 | observe | 21 | 0.286 | 4067 |
| ermaozi-get_subscribe | 0.335 | observe | 33 | 0.303 | 523 |
| Epodonios-all | 0.255 | observe | 0 | None | 7591 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10125 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5559 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.286 | 6 | 15 | 21 |
| ermaozi-get_subscribe | 0.303 | 10 | 23 | 33 |
| mheidari-all | 0.529 | 117 | 104 | 221 |
| zhangkai | 0.667 | 12 | 6 | 18 |
| Au1rxx-base64 | 0.88 | 257 | 35 | 292 |
| Surfboard-tg-mixed | 0.941 | 16 | 1 | 17 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24252 | yes | 6.04 | 0 |
| SoliSpirit-all | 10125 | yes | 6.26 | 0 |
| Epodonios-all | 7591 | yes | 8.36 | 0 |
| Surfboard-tg-mixed | 7097 | yes | 6.4 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.75 | 0 |
| barry-far-vless | 5773 | yes | 0.97 | 0 |
| Surfboard-tg-vless | 5559 | yes | 4.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 2.93 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 3.55 | 0 |
| DeltaKronecker-all | 4067 | yes | 6.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 90 |
| speed | 41 |
| 204 | 38 |
| cn-block | 17 |
