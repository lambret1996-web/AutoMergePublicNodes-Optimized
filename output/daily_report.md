# AutoNodes 每日报告

生成时间：2026-09-08 18:33:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 90700 |
| 去重后节点数 | 25007 |
| TCP 可达数 | 3000 |
| 真测通过数 | 492 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25007 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 89.5 |
| geo | 1.7 |
| probe | 325.4 |
| real_test | 291.0 |
| tcp | 43.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 35 | 25 | 10 | 71.4% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 161 | 147 | 14 | 91.3% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 21 | 10 | 11 | 47.6% |
| vless | 440 | 294 | 146 | 66.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 41 |
| 204:TimeoutError | 40 |
| geo:ClientOSError | 35 |
| 204:ProxyError | 21 |
| cn-block:TimeoutError | 21 |
| speed:TimeoutError | 7 |
| speed:ClientOSError | 7 |
| geo:TimeoutError | 7 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6099 |
| ConnectionRefusedError | 975 |
| gaierror | 390 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.948 | prefer | 302 | 0.884 | 1657 |
| Surfboard-tg-mixed | 0.784 | prefer | 140 | 0.707 | 7545 |
| ermaozi | 0.711 | prefer | 34 | 0.706 | 409 |
| mheidari-all | 0.585 | observe | 194 | 0.505 | 21346 |
| DeltaKronecker-all | 0.391 | observe | 2 | 1.0 | 6097 |
| tg-oneclickvpnkeys | 0.264 | observe | 1 | 1.0 | 224 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| Epodonios-all | 0.255 | observe | 0 | None | 7932 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.505 | 98 | 96 | 194 |
| ermaozi | 0.706 | 24 | 10 | 34 |
| Surfboard-tg-mixed | 0.707 | 99 | 41 | 140 |
| Au1rxx-base64 | 0.884 | 267 | 35 | 302 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21346 | yes | 4.0 | 0 |
| SoliSpirit-all | 9081 | yes | 3.07 | 0 |
| Epodonios-all | 7932 | yes | 2.34 | 0 |
| Surfboard-tg-mixed | 7545 | yes | 2.83 | 0 |
| barry-far-vless | 6498 | yes | 1.05 | 0 |
| Surfboard-tg-vless | 6277 | yes | 3.0 | 0 |
| DeltaKronecker-all | 6097 | yes | 4.22 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 2.16 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 0.51 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 64 |
| 204 | 63 |
| geo | 42 |
| speed | 14 |
