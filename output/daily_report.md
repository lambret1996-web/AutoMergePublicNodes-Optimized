# AutoNodes 每日报告

生成时间：2026-10-21 16:58:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 96596 |
| 去重后节点数 | 26903 |
| TCP 可达数 | 3000 |
| 真测通过数 | 361 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26903 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 85.3 |
| geo | 1.4 |
| probe | 267.1 |
| real_test | 260.0 |
| tcp | 46.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 42 | 15 | 27 | 35.7% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 153 | 129 | 24 | 84.3% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 102 | 57 | 45 | 55.9% |
| vless | 239 | 148 | 91 | 61.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 38 |
| 204:ProxyError | 35 |
| cn-block:TimeoutError | 34 |
| geo:ClientOSError | 19 |
| geo:TimeoutError | 18 |
| speed:TimeoutError | 18 |
| speed:ClientOSError | 13 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6946 |
| ConnectionRefusedError | 1017 |
| OSError | 234 |
| gaierror | 77 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.841 | prefer | 237 | 0.781 | 1568 |
| mheidari-all | 0.818 | prefer | 63 | 0.746 | 24102 |
| DeltaKronecker-all | 0.638 | observe | 145 | 0.559 | 4067 |
| Surfboard-tg-mixed | 0.603 | observe | 63 | 0.524 | 7070 |
| zhangkai | 0.518 | observe | 27 | 0.519 | 31 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| Epodonios-all | 0.255 | observe | 0 | None | 7559 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10165 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5554 |

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
| downweight | ermaozi-get_subscribe | 0.118 | 13 | 0.077 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.077 | 1 | 12 | 13 |
| zhangkai | 0.519 | 14 | 13 | 27 |
| Surfboard-tg-mixed | 0.524 | 33 | 30 | 63 |
| DeltaKronecker-all | 0.559 | 81 | 64 | 145 |
| mheidari-all | 0.746 | 47 | 16 | 63 |
| Au1rxx-base64 | 0.781 | 185 | 52 | 237 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24102 | yes | 3.05 | 0 |
| SoliSpirit-all | 10165 | yes | 2.79 | 0 |
| Epodonios-all | 7559 | yes | 3.29 | 0 |
| Surfboard-tg-mixed | 7070 | yes | 2.32 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5768 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 5554 | yes | 2.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 1.26 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 0.83 | 0 |
| DeltaKronecker-all | 4067 | yes | 3.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 77 |
| cn-block | 42 |
| geo | 40 |
| speed | 31 |
