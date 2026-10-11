# AutoNodes 每日报告

生成时间：2026-10-11 17:42:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 99904 |
| 去重后节点数 | 27587 |
| TCP 可达数 | 3000 |
| 真测通过数 | 479 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27587 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 87.4 |
| geo | 1.5 |
| probe | 344.9 |
| real_test | 362.8 |
| tcp | 47.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 1 | 7 | 12.5% |
| http | 19 | 9 | 10 | 47.4% |
| hysteria2 | 19 | 16 | 3 | 84.2% |
| shadowsocks | 140 | 122 | 18 | 87.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 168 | 156 | 12 | 92.9% |
| vless | 234 | 171 | 63 | 73.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 28 |
| 204:TimeoutError | 17 |
| 204:ProxyError | 14 |
| geo:ClientOSError | 14 |
| speed:TimeoutError | 13 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 6 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6566 |
| ConnectionRefusedError | 1029 |
| gaierror | 358 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | prefer | 361 | 0.909 | 1860 |
| mheidari-all | 0.849 | prefer | 50 | 0.78 | 23983 |
| DeltaKronecker-all | 0.78 | prefer | 28 | 0.714 | 5372 |
| Surfboard-tg-mixed | 0.726 | prefer | 125 | 0.648 | 7223 |
| ermaozi | 0.493 | observe | 18 | 0.5 | 635 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5099 |
| Epodonios-all | 0.255 | observe | 0 | None | 7642 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9946 |

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
| downweight | ermaozi-get_subscribe | 0.142 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.125 | 1 | 7 | 8 |
| ermaozi | 0.5 | 9 | 9 | 18 |
| Surfboard-tg-mixed | 0.648 | 81 | 44 | 125 |
| DeltaKronecker-all | 0.714 | 20 | 8 | 28 |
| mheidari-all | 0.78 | 39 | 11 | 50 |
| Au1rxx-base64 | 0.909 | 328 | 33 | 361 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23983 | yes | 4.13 | 0 |
| SoliSpirit-all | 9946 | yes | 3.62 | 0 |
| Epodonios-all | 7642 | yes | 4.66 | 0 |
| Surfboard-tg-mixed | 7223 | yes | 2.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.96 | 0 |
| barry-far-vless | 5910 | yes | 2.98 | 0 |
| Surfboard-tg-vless | 5723 | yes | 3.63 | 0 |
| DeltaKronecker-all | 5372 | yes | 5.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 5099 | yes | 2.85 | 0 |
| mahdibland-V2RayAggregator | 4318 | yes | 2.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 38 |
| 204 | 35 |
| speed | 22 |
| geo | 19 |
