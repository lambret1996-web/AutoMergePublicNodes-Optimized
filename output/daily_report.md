# AutoNodes 每日报告

生成时间：2026-09-30 12:36:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96416 |
| 去重后节点数 | 26887 |
| TCP 可达数 | 3000 |
| 真测通过数 | 453 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26887 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 87.5 |
| geo | 1.5 |
| probe | 327.0 |
| real_test | 220.6 |
| tcp | 45.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 55 | 45 | 10 | 81.8% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 156 | 140 | 16 | 89.7% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 31 | 12 | 19 | 38.7% |
| vless | 400 | 233 | 167 | 58.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 74 |
| 204:TimeoutError | 34 |
| 204:ProxyError | 21 |
| speed:TimeoutError | 21 |
| cn-block:TimeoutError | 21 |
| geo:TimeoutError | 17 |
| cn-block:ClientOSError | 15 |
| geo:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| 204:ClientOSError | 2 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6266 |
| ConnectionRefusedError | 1000 |
| gaierror | 374 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.872 | prefer | 46 | 0.804 | 22755 |
| Au1rxx-base64 | 0.855 | prefer | 281 | 0.786 | 1752 |
| ermaozi | 0.817 | prefer | 54 | 0.815 | 335 |
| Surfboard-tg-mixed | 0.622 | observe | 118 | 0.542 | 6952 |
| DeltaKronecker-all | 0.592 | observe | 162 | 0.512 | 5434 |
| tg-oneclickvpnkeys | 0.361 | observe | 3 | 1.0 | 68 |
| ermaozi-get_subscribe | 0.269 | observe | 1 | 1.0 | 353 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7458 |
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
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.512 | 83 | 79 | 162 |
| Surfboard-tg-mixed | 0.542 | 64 | 54 | 118 |
| Au1rxx-base64 | 0.786 | 221 | 60 | 281 |
| mheidari-all | 0.804 | 37 | 9 | 46 |
| ermaozi | 0.815 | 44 | 10 | 54 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22755 | yes | 6.76 | 0 |
| SoliSpirit-all | 9148 | yes | 2.64 | 0 |
| Epodonios-all | 7458 | yes | 3.58 | 0 |
| Surfboard-tg-mixed | 6952 | yes | 5.41 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.97 | 0 |
| barry-far-vless | 5879 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 5632 | yes | 4.43 | 0 |
| DeltaKronecker-all | 5434 | yes | 5.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 0.76 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 3.21 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 95 |
| 204 | 57 |
| cn-block | 39 |
| geo | 24 |
