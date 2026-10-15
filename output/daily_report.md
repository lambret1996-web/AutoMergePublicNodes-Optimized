# AutoNodes 每日报告

生成时间：2026-10-15 03:51:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 98808 |
| 去重后节点数 | 27485 |
| TCP 可达数 | 3000 |
| 真测通过数 | 438 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27485 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 72.4 |
| geo | 1.5 |
| probe | 261.6 |
| real_test | 325.1 |
| tcp | 47.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 59 | 26 | 33 | 44.1% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 156 | 146 | 10 | 93.6% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 41 | 36 | 5 | 87.8% |
| vless | 355 | 212 | 143 | 59.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 76 |
| 204:ProxyError | 36 |
| geo:ClientOSError | 29 |
| speed:ClientOSError | 14 |
| 204:TimeoutError | 13 |
| speed:TimeoutError | 10 |
| cn-block:TimeoutError | 7 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6876 |
| ConnectionRefusedError | 1044 |
| gaierror | 259 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.942 | prefer | 421 | 0.881 | 1576 |
| ermaozi | 0.48 | observe | 60 | 0.45 | 703 |
| mheidari-all | 0.366 | observe | 138 | 0.283 | 23886 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7681 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9917 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5728 |
| barry-far-vless | 0.255 | observe | 0 | None | 5978 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4271 |

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
| downweight | DeltaKronecker-all | 0.148 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.0 | 0 | 6 | 6 |
| Surfboard-tg-mixed | 0.25 | 1 | 3 | 4 |
| mheidari-all | 0.283 | 39 | 99 | 138 |
| ermaozi | 0.45 | 27 | 33 | 60 |
| Au1rxx-base64 | 0.881 | 371 | 50 | 421 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23886 | yes | 5.64 | 0 |
| SoliSpirit-all | 9917 | yes | 3.74 | 0 |
| Epodonios-all | 7681 | yes | 4.92 | 0 |
| Surfboard-tg-mixed | 7169 | yes | 4.11 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.52 | 0 |
| barry-far-vless | 5978 | yes | 3.04 | 0 |
| Surfboard-tg-vless | 5728 | yes | 3.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 2.23 | 0 |
| DeltaKronecker-all | 4803 | yes | 4.51 | 0 |
| mahdibland-V2RayAggregator | 4271 | yes | 2.55 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 106 |
| 204 | 52 |
| speed | 24 |
| cn-block | 13 |
