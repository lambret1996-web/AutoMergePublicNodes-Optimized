# AutoNodes 每日报告

生成时间：2026-10-01 05:44:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 97857 |
| 去重后节点数 | 27309 |
| TCP 可达数 | 3000 |
| 真测通过数 | 451 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27309 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 72.5 |
| geo | 1.6 |
| probe | 280.7 |
| real_test | 416.8 |
| tcp | 45.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 7 | 1 | 87.5% |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 140 | 129 | 11 | 92.1% |
| trojan | 38 | 22 | 16 | 57.9% |
| vless | 578 | 250 | 328 | 43.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 144 |
| speed:ClientOSError | 65 |
| speed:TimeoutError | 57 |
| geo:ClientOSError | 32 |
| 204:ProxyError | 26 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 10 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| geo:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6414 |
| ConnectionRefusedError | 1008 |
| gaierror | 405 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.937 | prefer | 21 | 0.952 | 588 |
| Au1rxx-base64 | 0.875 | prefer | 314 | 0.809 | 1694 |
| Surfboard-tg-mixed | 0.507 | observe | 8 | 0.75 | 7136 |
| mheidari-all | 0.443 | observe | 450 | 0.362 | 22835 |
| ermaozi-get_subscribe | 0.428 | observe | 6 | 0.833 | 487 |
| tg-oneclickvpnkeys | 0.314 | observe | 2 | 1.0 | 80 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7637 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9403 |

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
| downweight | DeltaKronecker-all | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.143 | 1 | 6 | 7 |
| mheidari-all | 0.362 | 163 | 287 | 450 |
| Surfboard-tg-mixed | 0.75 | 6 | 2 | 8 |
| Au1rxx-base64 | 0.809 | 254 | 60 | 314 |
| ermaozi-get_subscribe | 0.833 | 5 | 1 | 6 |
| ermaozi | 0.952 | 20 | 1 | 21 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22835 | yes | 4.5 | 0 |
| SoliSpirit-all | 9403 | yes | 1.9 | 0 |
| Epodonios-all | 7637 | yes | 2.55 | 0 |
| Surfboard-tg-mixed | 7136 | yes | 4.01 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.62 | 0 |
| barry-far-vless | 6001 | yes | 0.96 | 0 |
| Surfboard-tg-vless | 5815 | yes | 3.09 | 0 |
| DeltaKronecker-all | 5434 | yes | 4.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 0.78 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 1.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 178 |
| speed | 122 |
| 204 | 38 |
| cn-block | 19 |
