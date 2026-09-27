# AutoNodes 每日报告

生成时间：2026-09-27 05:16:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 95804 |
| 去重后节点数 | 26622 |
| TCP 可达数 | 3000 |
| 真测通过数 | 531 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26622 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 74.4 |
| geo | 1.7 |
| probe | 305.6 |
| real_test | 458.0 |
| tcp | 43.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 40 | 27 | 13 | 67.5% |
| hysteria2 | 22 | 19 | 3 | 86.4% |
| shadowsocks | 176 | 156 | 20 | 88.6% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 9 | 6 | 3 | 66.7% |
| vless | 709 | 321 | 388 | 45.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 177 |
| speed:TimeoutError | 75 |
| geo:ClientOSError | 60 |
| speed:ClientOSError | 36 |
| 204:TimeoutError | 22 |
| 204:ProxyError | 16 |
| cn-block:TimeoutError | 16 |
| cn-block:ClientOSError | 15 |
| 204:ProxyConnectionError | 8 |
| 204:ClientOSError | 5 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6341 |
| ConnectionRefusedError | 952 |
| gaierror | 326 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.937 | prefer | 279 | 0.878 | 1536 |
| Surfboard-tg-mixed | 0.792 | prefer | 130 | 0.715 | 7113 |
| ermaozi | 0.719 | prefer | 32 | 0.719 | 338 |
| mheidari-all | 0.406 | observe | 504 | 0.325 | 22408 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 66 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7583 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| downweight | ermaozi-get_subscribe | 0.207 | 7 | 0.286 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| ermaozi-get_subscribe | 0.286 | 2 | 5 | 7 |
| mheidari-all | 0.325 | 164 | 340 | 504 |
| Surfboard-tg-mixed | 0.715 | 93 | 37 | 130 |
| ermaozi | 0.719 | 23 | 9 | 32 |
| Au1rxx-base64 | 0.878 | 245 | 34 | 279 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22408 | yes | 4.66 | 0 |
| SoliSpirit-all | 8902 | yes | 3.4 | 0 |
| Epodonios-all | 7583 | yes | 2.55 | 0 |
| Surfboard-tg-mixed | 7113 | yes | 3.53 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.81 | 0 |
| barry-far-vless | 5907 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 5686 | yes | 3.27 | 0 |
| DeltaKronecker-all | 5512 | yes | 4.17 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 1.47 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 2.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 237 |
| speed | 112 |
| 204 | 51 |
| cn-block | 31 |
