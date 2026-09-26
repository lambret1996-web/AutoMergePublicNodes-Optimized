# AutoNodes 每日报告

生成时间：2026-09-26 21:07:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96520 |
| 去重后节点数 | 26455 |
| TCP 可达数 | 3000 |
| 真测通过数 | 397 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26455 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 89.9 |
| geo | 1.5 |
| probe | 249.5 |
| real_test | 174.7 |
| tcp | 43.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 21 | 10 | 11 | 47.6% |
| hysteria2 | 23 | 22 | 1 | 95.7% |
| shadowsocks | 158 | 144 | 14 | 91.1% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 23 | 11 | 12 | 47.8% |
| vless | 263 | 207 | 56 | 78.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 31 |
| cn-block:TimeoutError | 19 |
| cn-block:ClientOSError | 15 |
| 204:ProxyError | 12 |
| speed:TimeoutError | 6 |
| geo:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| speed:ClientOSError | 2 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5828 |
| ConnectionRefusedError | 949 |
| gaierror | 317 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.962 | prefer | 287 | 0.899 | 1654 |
| mheidari-all | 0.83 | prefer | 74 | 0.757 | 22366 |
| Surfboard-tg-mixed | 0.747 | prefer | 103 | 0.67 | 7263 |
| ermaozi | 0.433 | observe | 18 | 0.444 | 296 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 66 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7740 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |

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
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| ermaozi | 0.444 | 8 | 10 | 18 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| tg-LonUp_M | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.67 | 69 | 34 | 103 |
| mheidari-all | 0.757 | 56 | 18 | 74 |
| Au1rxx-base64 | 0.899 | 258 | 29 | 287 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22366 | yes | 5.94 | 0 |
| SoliSpirit-all | 8923 | yes | 3.82 | 0 |
| Epodonios-all | 7740 | yes | 4.01 | 0 |
| Surfboard-tg-mixed | 7263 | yes | 3.63 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.27 | 0 |
| barry-far-vless | 6052 | yes | 2.78 | 0 |
| Surfboard-tg-vless | 5823 | yes | 3.81 | 0 |
| DeltaKronecker-all | 5512 | yes | 6.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 2.59 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 2.76 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 47 |
| cn-block | 35 |
| speed | 8 |
| geo | 7 |
