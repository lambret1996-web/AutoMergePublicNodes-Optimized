# AutoNodes 每日报告

生成时间：2026-09-24 21:33:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98134 |
| 去重后节点数 | 26547 |
| TCP 可达数 | 3000 |
| 真测通过数 | 353 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26547 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 20.3 |
| generate | 74.0 |
| geo | 1.5 |
| probe | 186.8 |
| real_test | 165.4 |
| tcp | 43.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 15 | 10 | 5 | 66.7% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 159 | 143 | 16 | 89.9% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 12 | 9 | 3 | 75.0% |
| vless | 209 | 169 | 40 | 80.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 13 |
| cn-block:ClientOSError | 11 |
| 204:ProxyError | 10 |
| cn-block:TimeoutError | 10 |
| 204:ProxyConnectionError | 6 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| speed:ClientOSError | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6035 |
| ConnectionRefusedError | 979 |
| gaierror | 337 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | prefer | 257 | 0.911 | 1626 |
| Surfboard-tg-mixed | 0.858 | prefer | 52 | 0.788 | 7419 |
| mheidari-all | 0.827 | prefer | 85 | 0.753 | 22744 |
| ermaozi | 0.475 | observe | 13 | 0.615 | 298 |
| DeltaKronecker-all | 0.337 | observe | 7 | 0.429 | 5845 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4405 |
| ermaozi-get_subscribe | 0.267 | observe | 1 | 1.0 | 304 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 65 |
| Epodonios-all | 0.255 | observe | 0 | None | 7888 |
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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.429 | 3 | 4 | 7 |
| ermaozi | 0.615 | 8 | 5 | 13 |
| mheidari-all | 0.753 | 64 | 21 | 85 |
| Surfboard-tg-mixed | 0.788 | 41 | 11 | 52 |
| Au1rxx-base64 | 0.911 | 234 | 23 | 257 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22744 | yes | 5.73 | 0 |
| SoliSpirit-all | 9086 | yes | 4.16 | 0 |
| Epodonios-all | 7888 | yes | 3.37 | 0 |
| Surfboard-tg-mixed | 7419 | yes | 4.23 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.22 | 0 |
| barry-far-vless | 6215 | yes | 1.56 | 0 |
| Surfboard-tg-vless | 5963 | yes | 3.87 | 0 |
| DeltaKronecker-all | 5845 | yes | 6.44 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 4405 | yes | 2.96 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 32 |
| cn-block | 22 |
| speed | 8 |
| geo | 5 |
