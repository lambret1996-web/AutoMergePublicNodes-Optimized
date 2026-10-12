# AutoNodes 每日报告

生成时间：2026-10-12 05:08:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99740 |
| 去重后节点数 | 27634 |
| TCP 可达数 | 3000 |
| 真测通过数 | 499 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27634 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 93.5 |
| geo | 1.3 |
| probe | 352.5 |
| real_test | 541.2 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 51 | 32 | 19 | 62.7% |
| hysteria2 | 27 | 27 | 0 | 100.0% |
| shadowsocks | 132 | 125 | 7 | 94.7% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 180 | 165 | 15 | 91.7% |
| vless | 402 | 146 | 256 | 36.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 132 |
| speed:TimeoutError | 57 |
| geo:ClientOSError | 29 |
| 204:ProxyError | 28 |
| speed:ClientOSError | 18 |
| 204:TimeoutError | 13 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6506 |
| ConnectionRefusedError | 1058 |
| gaierror | 405 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | prefer | 393 | 0.901 | 1810 |
| DeltaKronecker-all | 0.736 | prefer | 59 | 0.661 | 5372 |
| ermaozi | 0.689 | observe | 51 | 0.667 | 708 |
| Surfboard-tg-mixed | 0.43 | observe | 9 | 0.556 | 7200 |
| SoliSpirit-all | 0.335 | observe | 1 | 1.0 | 9918 |
| mheidari-all | 0.315 | observe | 279 | 0.233 | 23656 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| Epodonios-all | 0.255 | observe | 0 | None | 7699 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5717 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.233 | 65 | 214 | 279 |
| Surfboard-tg-mixed | 0.556 | 5 | 4 | 9 |
| DeltaKronecker-all | 0.661 | 39 | 20 | 59 |
| ermaozi | 0.667 | 34 | 17 | 51 |
| Au1rxx-base64 | 0.901 | 354 | 39 | 393 |
| SoliSpirit-all | 1.0 | 1 | 0 | 1 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23656 | yes | 4.45 | 0 |
| SoliSpirit-all | 9918 | yes | 3.5 | 0 |
| Epodonios-all | 7699 | yes | 4.62 | 0 |
| Surfboard-tg-mixed | 7200 | yes | 3.27 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.08 | 0 |
| barry-far-vless | 5961 | yes | 2.48 | 0 |
| Surfboard-tg-vless | 5717 | yes | 3.05 | 0 |
| DeltaKronecker-all | 5372 | yes | 5.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 5099 | yes | 1.39 | 0 |
| mahdibland-V2RayAggregator | 4284 | yes | 1.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 162 |
| speed | 75 |
| 204 | 42 |
| cn-block | 20 |
