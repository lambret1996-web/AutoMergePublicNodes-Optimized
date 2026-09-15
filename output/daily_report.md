# AutoNodes 每日报告

生成时间：2026-09-15 12:32:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 90388 |
| 去重后节点数 | 25595 |
| TCP 可达数 | 3000 |
| 真测通过数 | 438 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25595 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 74.9 |
| geo | 1.5 |
| probe | 261.0 |
| real_test | 235.6 |
| tcp | 42.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 48 | 32 | 16 | 66.7% |
| hysteria2 | 22 | 18 | 4 | 81.8% |
| shadowsocks | 155 | 139 | 16 | 89.7% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 26 | 22 | 4 | 84.6% |
| vless | 330 | 225 | 105 | 68.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 41 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 19 |
| 204:TimeoutError | 16 |
| speed:ClientOSError | 12 |
| geo:TimeoutError | 11 |
| cn-block:ClientOSError | 10 |
| speed:TimeoutError | 9 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6106 |
| ConnectionRefusedError | 954 |
| gaierror | 321 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.909 | prefer | 308 | 0.854 | 1440 |
| Surfboard-tg-mixed | 0.727 | prefer | 131 | 0.649 | 7608 |
| ermaozi | 0.67 | observe | 47 | 0.66 | 425 |
| mheidari-all | 0.66 | observe | 86 | 0.581 | 21594 |
| DeltaKronecker-all | 0.53 | observe | 10 | 0.7 | 5932 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 148 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 8076 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.581 | 50 | 36 | 86 |
| Surfboard-tg-mixed | 0.649 | 85 | 46 | 131 |
| ermaozi | 0.66 | 31 | 16 | 47 |
| DeltaKronecker-all | 0.7 | 7 | 3 | 10 |
| Au1rxx-base64 | 0.854 | 263 | 45 | 308 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21594 | yes | 5.44 | 0 |
| SoliSpirit-all | 8760 | yes | 1.47 | 0 |
| Epodonios-all | 8076 | yes | 5.64 | 0 |
| Surfboard-tg-mixed | 7608 | yes | 3.43 | 0 |
| barry-far-vless | 6401 | yes | 0.97 | 0 |
| Surfboard-tg-vless | 6177 | yes | 3.21 | 0 |
| DeltaKronecker-all | 5932 | yes | 3.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.16 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 1.15 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 52 |
| 204 | 40 |
| cn-block | 34 |
| speed | 22 |
