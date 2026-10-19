# AutoNodes 每日报告

生成时间：2026-10-19 18:38:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 94583 |
| 去重后节点数 | 26114 |
| TCP 可达数 | 3000 |
| 真测通过数 | 318 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26114 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 80.8 |
| geo | 1.5 |
| probe | 277.7 |
| real_test | 210.8 |
| tcp | 44.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 15 | 8 | 7 | 53.3% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 136 | 115 | 21 | 84.6% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 29 | 12 | 17 | 41.4% |
| vless | 242 | 170 | 72 | 70.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 30 |
| cn-block:TimeoutError | 27 |
| 204:ProxyError | 14 |
| speed:TimeoutError | 12 |
| speed:ClientOSError | 11 |
| 204:ProxyConnectionError | 10 |
| cn-block:ClientOSError | 6 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6379 |
| ConnectionRefusedError | 1044 |
| gaierror | 265 |
| OSError | 240 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.852 | prefer | 362 | 0.79 | 1580 |
| mheidari-all | 0.701 | prefer | 27 | 0.63 | 23148 |
| zhangkai | 0.478 | observe | 6 | 1.0 | 27 |
| Surfboard-tg-mixed | 0.4 | observe | 23 | 0.304 | 7064 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 86 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| Epodonios-all | 0.255 | observe | 0 | None | 7406 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9916 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5579 |

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
| downweight | DeltaKronecker-all | 0.133 | 12 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ermaozi-get_subscribe | 0.142 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.0 | 0 | 12 | 12 |
| ermaozi-get_subscribe | 0.125 | 1 | 7 | 8 |
| Surfboard-tg-mixed | 0.304 | 7 | 16 | 23 |
| mheidari-all | 0.63 | 17 | 10 | 27 |
| Au1rxx-base64 | 0.79 | 286 | 76 | 362 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 6 | 0 | 6 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23148 | yes | 5.45 | 0 |
| SoliSpirit-all | 9916 | yes | 3.89 | 0 |
| Epodonios-all | 7406 | yes | 6.38 | 0 |
| Surfboard-tg-mixed | 7064 | yes | 3.66 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.07 | 0 |
| barry-far-vless | 5654 | yes | 4.17 | 0 |
| Surfboard-tg-vless | 5579 | yes | 3.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 3.46 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 0.15 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.54 | 0 |

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
| 204 | 57 |
| cn-block | 34 |
| speed | 23 |
| geo | 7 |
