# AutoNodes 每日报告

生成时间：2026-09-29 05:41:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96798 |
| 去重后节点数 | 27003 |
| TCP 可达数 | 3000 |
| 真测通过数 | 550 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27003 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 75.3 |
| geo | 1.7 |
| probe | 299.3 |
| real_test | 413.5 |
| tcp | 44.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 38 | 28 | 10 | 73.7% |
| hysteria2 | 26 | 25 | 1 | 96.2% |
| shadowsocks | 187 | 179 | 8 | 95.7% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 27 | 23 | 4 | 85.2% |
| vless | 652 | 289 | 363 | 44.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 131 |
| speed:TimeoutError | 74 |
| speed:ClientOSError | 70 |
| geo:ClientOSError | 49 |
| 204:ProxyError | 23 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6325 |
| ConnectionRefusedError | 987 |
| gaierror | 391 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.875 | prefer | 351 | 0.812 | 1609 |
| Surfboard-tg-mixed | 0.79 | prefer | 208 | 0.712 | 7005 |
| ermaozi | 0.757 | prefer | 33 | 0.758 | 354 |
| DeltaKronecker-all | 0.407 | observe | 11 | 0.455 | 5428 |
| mheidari-all | 0.332 | observe | 327 | 0.251 | 22589 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| ermaozi-get_subscribe | 0.308 | observe | 5 | 0.6 | 367 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 121 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5326 |
| Epodonios-all | 0.255 | observe | 0 | None | 7625 |

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
| mheidari-all | 0.251 | 82 | 245 | 327 |
| DeltaKronecker-all | 0.455 | 5 | 6 | 11 |
| ermaozi-get_subscribe | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.712 | 148 | 60 | 208 |
| ermaozi | 0.758 | 25 | 8 | 33 |
| Au1rxx-base64 | 0.812 | 285 | 66 | 351 |
| ninja-vless | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22589 | yes | 5.55 | 0 |
| SoliSpirit-all | 9567 | yes | 4.3 | 0 |
| Epodonios-all | 7625 | yes | 0.92 | 0 |
| Surfboard-tg-mixed | 7005 | yes | 3.36 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.58 | 0 |
| barry-far-vless | 6028 | yes | 3.23 | 0 |
| Surfboard-tg-vless | 5633 | yes | 3.78 | 0 |
| DeltaKronecker-all | 5428 | yes | 5.14 | 0 |
| 10ium-ScrapeCategorize-Vless | 5326 | yes | 2.92 | 0 |
| mahdibland-V2RayAggregator | 4237 | yes | 0.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 181 |
| speed | 145 |
| 204 | 43 |
| cn-block | 19 |
