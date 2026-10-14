# AutoNodes 每日报告

生成时间：2026-10-14 16:56:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98394 |
| 去重后节点数 | 27299 |
| TCP 可达数 | 3000 |
| 真测通过数 | 362 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27299 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 75.2 |
| geo | 1.4 |
| probe | 298.7 |
| real_test | 298.3 |
| tcp | 48.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 31 | 23 | 8 | 74.2% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 134 | 119 | 15 | 88.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 74 | 56 | 18 | 75.7% |
| vless | 233 | 153 | 80 | 65.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 30 |
| 204:TimeoutError | 30 |
| 204:ProxyError | 15 |
| speed:TimeoutError | 10 |
| geo:ClientOSError | 9 |
| speed:ClientOSError | 8 |
| geo:TimeoutError | 8 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 4 |
| cn-block:ProxyError | 2 |
| cn-block:status | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7140 |
| ConnectionRefusedError | 1026 |
| gaierror | 242 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| mheidari-all | 0.928 | prefer | 44 | 0.864 | 23968 |
| Au1rxx-base64 | 0.871 | prefer | 287 | 0.801 | 1780 |
| Surfboard-tg-mixed | 0.663 | observe | 94 | 0.585 | 7210 |
| DeltaKronecker-all | 0.647 | observe | 28 | 0.571 | 4803 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7543 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9997 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5726 |

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
| downweight | ermaozi-get_subscribe | 0.082 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 8 | 8 |
| DeltaKronecker-all | 0.571 | 16 | 12 | 28 |
| Surfboard-tg-mixed | 0.585 | 55 | 39 | 94 |
| Au1rxx-base64 | 0.801 | 230 | 57 | 287 |
| mheidari-all | 0.864 | 38 | 6 | 44 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23968 | yes | 3.53 | 0 |
| SoliSpirit-all | 9997 | yes | 2.11 | 0 |
| Epodonios-all | 7543 | yes | 3.05 | 0 |
| Surfboard-tg-mixed | 7210 | yes | 3.75 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.69 | 0 |
| barry-far-vless | 5831 | yes | 1.34 | 0 |
| Surfboard-tg-vless | 5726 | yes | 2.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 1.23 | 0 |
| DeltaKronecker-all | 4803 | yes | 3.02 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 1.01 | 0 |

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
| 204 | 46 |
| cn-block | 38 |
| geo | 21 |
| speed | 19 |
