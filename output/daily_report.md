# AutoNodes 每日报告

生成时间：2026-09-28 23:18:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97528 |
| 去重后节点数 | 27020 |
| TCP 可达数 | 3000 |
| 真测通过数 | 429 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27020 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 71.3 |
| geo | 1.4 |
| probe | 216.7 |
| real_test | 148.3 |
| tcp | 45.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 32 | 16 | 16 | 50.0% |
| hysteria2 | 24 | 24 | 0 | 100.0% |
| shadowsocks | 191 | 180 | 11 | 94.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 11 | 9 | 2 | 81.8% |
| vless | 244 | 196 | 48 | 80.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 28 |
| 204:ProxyError | 11 |
| cn-block:TimeoutError | 8 |
| 204:ProxyConnectionError | 6 |
| speed:TimeoutError | 6 |
| 204:TimeoutError | 6 |
| geo:TimeoutError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6423 |
| ConnectionRefusedError | 1002 |
| gaierror | 378 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.992 | prefer | 55 | 0.927 | 7142 |
| Au1rxx-base64 | 0.936 | prefer | 310 | 0.871 | 1674 |
| mheidari-all | 0.907 | prefer | 108 | 0.833 | 22856 |
| ermaozi | 0.565 | observe | 27 | 0.556 | 344 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 5428 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 121 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5326 |
| Epodonios-all | 0.255 | observe | 0 | None | 7535 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9706 |

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
| downweight | ermaozi-get_subscribe | 0.161 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| ermaozi | 0.556 | 15 | 12 | 27 |
| mheidari-all | 0.833 | 90 | 18 | 108 |
| Au1rxx-base64 | 0.871 | 270 | 40 | 310 |
| Surfboard-tg-mixed | 0.927 | 51 | 4 | 55 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22856 | yes | 4.84 | 0 |
| SoliSpirit-all | 9706 | yes | 1.56 | 0 |
| Epodonios-all | 7535 | yes | 2.36 | 0 |
| Surfboard-tg-mixed | 7142 | yes | 3.41 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.06 | 0 |
| barry-far-vless | 6027 | yes | 1.06 | 0 |
| Surfboard-tg-vless | 5799 | yes | 2.78 | 0 |
| DeltaKronecker-all | 5428 | yes | 5.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 5326 | yes | 0.88 | 0 |
| mahdibland-V2RayAggregator | 4237 | yes | 2.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 35 |
| 204 | 26 |
| cn-block | 10 |
| geo | 7 |
