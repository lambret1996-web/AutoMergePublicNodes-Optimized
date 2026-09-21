# AutoNodes 每日报告

生成时间：2026-09-21 12:29:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 84518 |
| 去重后节点数 | 23404 |
| TCP 可达数 | 3000 |
| 真测通过数 | 501 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23404 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 75.7 |
| geo | 1.4 |
| probe | 180.9 |
| real_test | 215.7 |
| tcp | 38.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 42 | 31 | 11 | 73.8% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 168 | 152 | 16 | 90.5% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 29 | 25 | 4 | 86.2% |
| vless | 393 | 274 | 119 | 69.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 32 |
| geo:TimeoutError | 23 |
| 204:ProxyError | 21 |
| 204:TimeoutError | 20 |
| cn-block:ClientOSError | 15 |
| speed:ClientOSError | 14 |
| cn-block:TimeoutError | 13 |
| speed:TimeoutError | 12 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5658 |
| ConnectionRefusedError | 787 |
| gaierror | 152 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.943 | prefer | 275 | 0.88 | 1649 |
| DeltaKronecker-all | 0.88 | prefer | 43 | 0.814 | 6181 |
| mheidari-all | 0.818 | prefer | 78 | 0.744 | 16192 |
| ermaozi | 0.746 | prefer | 39 | 0.744 | 355 |
| Surfboard-tg-mixed | 0.705 | prefer | 214 | 0.626 | 7246 |
| tg-oneclickvpnkeys | 0.273 | observe | 3 | 0.667 | 108 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5290 |
| Epodonios-all | 0.255 | observe | 0 | None | 7697 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.626 | 134 | 80 | 214 |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| ermaozi | 0.744 | 29 | 10 | 39 |
| mheidari-all | 0.744 | 58 | 20 | 78 |
| DeltaKronecker-all | 0.814 | 35 | 8 | 43 |
| Au1rxx-base64 | 0.88 | 242 | 33 | 275 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16192 | yes | 2.92 | 0 |
| SoliSpirit-all | 8900 | yes | 1.52 | 0 |
| Epodonios-all | 7697 | yes | 3.07 | 0 |
| Surfboard-tg-mixed | 7246 | yes | 2.14 | 0 |
| DeltaKronecker-all | 6181 | yes | 1.92 | 0 |
| barry-far-vless | 6062 | yes | 0.69 | 0 |
| Surfboard-tg-vless | 5845 | yes | 2.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 0.82 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 1.87 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 0.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 56 |
| 204 | 42 |
| cn-block | 29 |
| speed | 26 |
