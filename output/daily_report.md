# AutoNodes 每日报告

生成时间：2026-09-25 21:34:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97228 |
| 去重后节点数 | 26475 |
| TCP 可达数 | 3000 |
| 真测通过数 | 403 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26475 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 75.0 |
| geo | 1.4 |
| probe | 204.5 |
| real_test | 149.0 |
| tcp | 43.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 35 | 24 | 11 | 68.6% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 159 | 142 | 17 | 89.3% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 28 | 24 | 4 | 85.7% |
| vless | 241 | 188 | 53 | 78.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 27 |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 15 |
| speed:ClientOSError | 6 |
| geo:TimeoutError | 5 |
| speed:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6272 |
| ConnectionRefusedError | 951 |
| gaierror | 328 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.967 | prefer | 248 | 0.903 | 1671 |
| mheidari-all | 0.901 | prefer | 82 | 0.829 | 22345 |
| Surfboard-tg-mixed | 0.774 | prefer | 122 | 0.697 | 7370 |
| ermaozi | 0.698 | observe | 33 | 0.697 | 304 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 5452 |
| ermaozi-get_subscribe | 0.268 | observe | 1 | 1.0 | 314 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7740 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9253 |

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
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.697 | 23 | 10 | 33 |
| Surfboard-tg-mixed | 0.697 | 85 | 37 | 122 |
| mheidari-all | 0.829 | 68 | 14 | 82 |
| Au1rxx-base64 | 0.903 | 224 | 24 | 248 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22345 | yes | 3.53 | 0 |
| SoliSpirit-all | 9253 | yes | 1.41 | 0 |
| Epodonios-all | 7740 | yes | 1.82 | 0 |
| Surfboard-tg-mixed | 7370 | yes | 2.68 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.03 | 0 |
| barry-far-vless | 6190 | yes | 0.66 | 0 |
| Surfboard-tg-vless | 5959 | yes | 3.64 | 0 |
| DeltaKronecker-all | 5452 | yes | 2.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 0.44 | 0 |
| mahdibland-V2RayAggregator | 4304 | yes | 1.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 46 |
| cn-block | 24 |
| speed | 13 |
| geo | 5 |
