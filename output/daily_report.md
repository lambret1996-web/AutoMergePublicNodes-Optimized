# AutoNodes 每日报告

生成时间：2026-09-22 00:41:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 92055 |
| 去重后节点数 | 25204 |
| TCP 可达数 | 3000 |
| 真测通过数 | 597 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25204 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 84.3 |
| geo | 3.0 |
| probe | 352.9 |
| real_test | 576.9 |
| tcp | 42.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 37 | 26 | 11 | 70.3% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 155 | 151 | 4 | 97.4% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 23 | 13 | 10 | 56.5% |
| vless | 1008 | 385 | 623 | 38.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 234 |
| geo:ClientOSError | 127 |
| speed:ClientOSError | 97 |
| speed:TimeoutError | 75 |
| cn-block:ClientOSError | 59 |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 14 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5599 |
| ConnectionRefusedError | 925 |
| gaierror | 372 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | prefer | 271 | 0.819 | 1696 |
| Surfboard-tg-mixed | 0.866 | prefer | 82 | 0.793 | 7121 |
| ermaozi | 0.698 | observe | 36 | 0.694 | 350 |
| mheidari-all | 0.518 | observe | 407 | 0.437 | 20197 |
| DeltaKronecker-all | 0.315 | observe | 440 | 0.234 | 6181 |
| 10ium-ScrapeCategorize-Vless | 0.272 | observe | 7 | 0.286 | 5290 |
| ermaozi-get_subscribe | 0.27 | observe | 1 | 1.0 | 377 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7569 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.234 | 103 | 337 | 440 |
| 10ium-ScrapeCategorize-Vless | 0.286 | 2 | 5 | 7 |
| mheidari-all | 0.437 | 178 | 229 | 407 |
| ermaozi | 0.694 | 25 | 11 | 36 |
| Surfboard-tg-mixed | 0.793 | 65 | 17 | 82 |
| Au1rxx-base64 | 0.819 | 222 | 49 | 271 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20197 | yes | 5.59 | 0 |
| SoliSpirit-all | 8704 | yes | 6.83 | 0 |
| Epodonios-all | 7569 | yes | 6.44 | 0 |
| Surfboard-tg-mixed | 7121 | yes | 4.51 | 0 |
| DeltaKronecker-all | 6181 | yes | 5.87 | 0 |
| barry-far-vless | 5885 | yes | 1.6 | 0 |
| Surfboard-tg-vless | 5672 | yes | 4.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 3.26 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 0.46 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 1.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 363 |
| speed | 172 |
| cn-block | 79 |
| 204 | 38 |
