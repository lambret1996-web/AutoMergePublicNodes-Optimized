# AutoNodes 每日报告

生成时间：2026-09-26 11:23:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96784 |
| 去重后节点数 | 26417 |
| TCP 可达数 | 3000 |
| 真测通过数 | 369 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26417 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 80.3 |
| geo | 1.5 |
| probe | 283.7 |
| real_test | 174.5 |
| tcp | 43.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 39 | 19 | 20 | 48.7% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 152 | 132 | 20 | 86.8% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 35 | 30 | 5 | 85.7% |
| vless | 256 | 165 | 91 | 64.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 33 |
| 204:ProxyError | 25 |
| cn-block:ClientOSError | 25 |
| cn-block:TimeoutError | 14 |
| geo:TimeoutError | 14 |
| speed:TimeoutError | 12 |
| 204:ProxyConnectionError | 7 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |
| geo:ClientOSError | 2 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6202 |
| ConnectionRefusedError | 963 |
| gaierror | 375 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.942 | prefer | 231 | 0.879 | 1660 |
| Surfboard-tg-mixed | 0.731 | prefer | 127 | 0.654 | 7247 |
| mheidari-all | 0.657 | observe | 102 | 0.578 | 22392 |
| ermaozi | 0.477 | observe | 39 | 0.462 | 352 |
| DeltaKronecker-all | 0.421 | observe | 6 | 0.667 | 5512 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7713 |
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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.462 | 18 | 21 | 39 |
| mheidari-all | 0.578 | 59 | 43 | 102 |
| Surfboard-tg-mixed | 0.654 | 83 | 44 | 127 |
| DeltaKronecker-all | 0.667 | 4 | 2 | 6 |
| Au1rxx-base64 | 0.879 | 203 | 28 | 231 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22392 | yes | 5.66 | 0 |
| SoliSpirit-all | 8992 | yes | 4.09 | 0 |
| Epodonios-all | 7713 | yes | 3.47 | 0 |
| Surfboard-tg-mixed | 7247 | yes | 6.64 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.77 | 0 |
| barry-far-vless | 6071 | yes | 0.81 | 0 |
| Surfboard-tg-vless | 5840 | yes | 4.06 | 0 |
| DeltaKronecker-all | 5512 | yes | 6.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 5.09 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 2.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 67 |
| cn-block | 41 |
| geo | 18 |
| speed | 14 |
