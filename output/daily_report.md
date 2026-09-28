# AutoNodes 每日报告

生成时间：2026-09-28 13:46:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96149 |
| 去重后节点数 | 26790 |
| TCP 可达数 | 3000 |
| 真测通过数 | 455 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26790 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 92.4 |
| geo | 1.5 |
| probe | 218.3 |
| real_test | 197.1 |
| tcp | 44.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 52 | 32 | 20 | 61.5% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 175 | 152 | 23 | 86.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 32 | 27 | 5 | 84.4% |
| vless | 294 | 222 | 72 | 75.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 23 |
| 204:ProxyError | 20 |
| 204:TimeoutError | 20 |
| speed:ClientOSError | 19 |
| geo:TimeoutError | 14 |
| speed:TimeoutError | 10 |
| 204:ProxyConnectionError | 6 |
| cn-block:ClientOSError | 4 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6355 |
| ConnectionRefusedError | 973 |
| gaierror | 347 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.957 | prefer | 55 | 0.891 | 22474 |
| Au1rxx-base64 | 0.877 | prefer | 313 | 0.812 | 1677 |
| Surfboard-tg-mixed | 0.839 | prefer | 139 | 0.763 | 7046 |
| ermaozi | 0.693 | observe | 51 | 0.686 | 344 |
| DeltaKronecker-all | 0.53 | observe | 10 | 0.7 | 5428 |
| tg-oneclickvpnkeys | 0.315 | observe | 2 | 1.0 | 94 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5326 |
| Epodonios-all | 0.255 | observe | 0 | None | 7414 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-OutlineReleasedKey | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| ermaozi | 0.686 | 35 | 16 | 51 |
| DeltaKronecker-all | 0.7 | 7 | 3 | 10 |
| Surfboard-tg-mixed | 0.763 | 106 | 33 | 139 |
| Au1rxx-base64 | 0.812 | 254 | 59 | 313 |
| mheidari-all | 0.891 | 49 | 6 | 55 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22474 | yes | 6.2 | 0 |
| SoliSpirit-all | 9420 | yes | 4.89 | 0 |
| Epodonios-all | 7414 | yes | 7.0 | 0 |
| Surfboard-tg-mixed | 7046 | yes | 4.38 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.07 | 0 |
| barry-far-vless | 5752 | yes | 3.28 | 0 |
| Surfboard-tg-vless | 5638 | yes | 4.14 | 0 |
| DeltaKronecker-all | 5428 | yes | 6.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 5326 | yes | 3.06 | 0 |
| mahdibland-V2RayAggregator | 4185 | yes | 2.01 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 48 |
| speed | 31 |
| cn-block | 28 |
| geo | 16 |
