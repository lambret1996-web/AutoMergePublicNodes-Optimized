# AutoNodes 每日报告

生成时间：2026-10-05 20:29:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98500 |
| 去重后节点数 | 27364 |
| TCP 可达数 | 3000 |
| 真测通过数 | 450 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27364 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 81.7 |
| geo | 1.5 |
| probe | 257.0 |
| real_test | 172.3 |
| tcp | 46.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 1 | 2 | 33.3% |
| http | 70 | 39 | 31 | 55.7% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 144 | 129 | 15 | 89.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 93 | 83 | 10 | 89.2% |
| vless | 231 | 183 | 48 | 79.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 32 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 14 |
| geo:ClientOSError | 9 |
| speed:TimeoutError | 8 |
| speed:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| 204:ProxyConnectionError | 4 |
| cn-block:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| 204:ClientOSError | 1 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6035 |
| ConnectionRefusedError | 1052 |
| gaierror | 383 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.968 | prefer | 319 | 0.897 | 1855 |
| mheidari-all | 0.924 | prefer | 43 | 0.86 | 23179 |
| Surfboard-tg-mixed | 0.832 | prefer | 99 | 0.758 | 7145 |
| ermaozi | 0.584 | observe | 70 | 0.557 | 701 |
| DeltaKronecker-all | 0.58 | observe | 20 | 0.5 | 5300 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5111 |
| Epodonios-all | 0.255 | observe | 0 | None | 7624 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.5 | 10 | 10 | 20 |
| ermaozi | 0.557 | 39 | 31 | 70 |
| Surfboard-tg-mixed | 0.758 | 75 | 24 | 99 |
| mheidari-all | 0.86 | 37 | 6 | 43 |
| Au1rxx-base64 | 0.897 | 286 | 33 | 319 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23179 | yes | 6.49 | 0 |
| SoliSpirit-all | 9342 | yes | 6.21 | 0 |
| Epodonios-all | 7624 | yes | 4.22 | 0 |
| Surfboard-tg-mixed | 7145 | yes | 5.74 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5930 | yes | 3.38 | 0 |
| Surfboard-tg-vless | 5642 | yes | 3.99 | 0 |
| DeltaKronecker-all | 5300 | yes | 6.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 5111 | yes | 3.89 | 0 |
| mahdibland-V2RayAggregator | 4375 | yes | 3.7 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 59 |
| cn-block | 22 |
| speed | 14 |
| geo | 13 |
