# AutoNodes 每日报告

生成时间：2026-09-29 12:47:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 96889 |
| 去重后节点数 | 26973 |
| TCP 可达数 | 3000 |
| 真测通过数 | 453 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26973 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 88.1 |
| geo | 1.6 |
| probe | 257.0 |
| real_test | 177.2 |
| tcp | 45.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 23 | 5 | 82.1% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 171 | 155 | 16 | 90.6% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 34 | 22 | 12 | 64.7% |
| vless | 305 | 228 | 77 | 74.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 27 |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 21 |
| 204:ProxyError | 14 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 9 |
| geo:TimeoutError | 6 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42638: bind: address already in use | 1 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6546 |
| ConnectionRefusedError | 1012 |
| gaierror | 293 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.965 | prefer | 50 | 0.9 | 22883 |
| Au1rxx-base64 | 0.916 | prefer | 335 | 0.854 | 1598 |
| ermaozi | 0.769 | prefer | 31 | 0.774 | 291 |
| Surfboard-tg-mixed | 0.749 | prefer | 137 | 0.672 | 7053 |
| DeltaKronecker-all | 0.45 | observe | 12 | 0.5 | 5528 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5314 |
| Epodonios-all | 0.255 | observe | 0 | None | 7502 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9548 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5690 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 6 | 6 | 12 |
| Surfboard-tg-mixed | 0.672 | 92 | 45 | 137 |
| ermaozi | 0.774 | 24 | 7 | 31 |
| Au1rxx-base64 | 0.854 | 286 | 49 | 335 |
| mheidari-all | 0.9 | 45 | 5 | 50 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22883 | yes | 6.53 | 0 |
| SoliSpirit-all | 9548 | yes | 4.44 | 0 |
| Epodonios-all | 7502 | yes | 3.15 | 0 |
| Surfboard-tg-mixed | 7053 | yes | 4.39 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.48 | 0 |
| barry-far-vless | 5869 | yes | 0.64 | 0 |
| Surfboard-tg-vless | 5690 | yes | 3.6 | 0 |
| DeltaKronecker-all | 5528 | yes | 5.03 | 0 |
| 10ium-ScrapeCategorize-Vless | 5314 | yes | 2.09 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 2.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 37 |
| 204 | 36 |
| cn-block | 33 |
| geo | 7 |
| sing-box exited 1 | 1 |
