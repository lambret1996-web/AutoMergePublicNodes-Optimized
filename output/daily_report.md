# AutoNodes 每日报告

生成时间：2026-09-17 06:35:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 86343 |
| 去重后节点数 | 24246 |
| TCP 可达数 | 3000 |
| 真测通过数 | 493 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24246 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 75.0 |
| geo | 1.4 |
| probe | 273.9 |
| real_test | 332.2 |
| tcp | 40.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 76 | 47 | 29 | 61.8% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 172 | 161 | 11 | 93.6% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 64 | 30 | 34 | 46.9% |
| vless | 403 | 227 | 176 | 56.3% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 77 |
| geo:ClientOSError | 38 |
| 204:ProxyError | 37 |
| speed:TimeoutError | 29 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 16 |
| cn-block:ClientOSError | 11 |
| 204:ClientOSError | 2 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5700 |
| ConnectionRefusedError | 917 |
| gaierror | 441 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.901 | prefer | 274 | 0.839 | 1590 |
| ermaozi | 0.745 | prefer | 57 | 0.737 | 396 |
| mheidari-all | 0.689 | observe | 85 | 0.612 | 17792 |
| Surfboard-tg-mixed | 0.683 | observe | 212 | 0.604 | 7408 |
| DeltaKronecker-all | 0.442 | observe | 92 | 0.359 | 6081 |
| ermaozi-get_subscribe | 0.365 | observe | 21 | 0.333 | 431 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 160 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5093 |
| Epodonios-all | 0.255 | observe | 0 | None | 7876 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| Pawdroid | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.333 | 7 | 14 | 21 |
| DeltaKronecker-all | 0.359 | 33 | 59 | 92 |
| Surfboard-tg-mixed | 0.604 | 128 | 84 | 212 |
| mheidari-all | 0.612 | 52 | 33 | 85 |
| ermaozi | 0.737 | 42 | 15 | 57 |
| Au1rxx-base64 | 0.839 | 230 | 44 | 274 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17792 | yes | 4.34 | 0 |
| SoliSpirit-all | 8898 | yes | 5.7 | 0 |
| Epodonios-all | 7876 | yes | 5.89 | 0 |
| Surfboard-tg-mixed | 7408 | yes | 6.22 | 0 |
| barry-far-vless | 6158 | yes | 0.95 | 0 |
| DeltaKronecker-all | 6081 | yes | 5.53 | 0 |
| Surfboard-tg-vless | 5925 | yes | 5.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 2.54 | 0 |
| mahdibland-V2RayAggregator | 4179 | yes | 2.86 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.85 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 116 |
| 204 | 56 |
| speed | 49 |
| cn-block | 32 |
