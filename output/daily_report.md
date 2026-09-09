# AutoNodes 每日报告

生成时间：2026-09-09 12:33:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85006 |
| 去重后节点数 | 22116 |
| TCP 可达数 | 3000 |
| 真测通过数 | 444 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22116 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 94.5 |
| geo | 1.4 |
| probe | 247.8 |
| real_test | 263.1 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 58 | 35 | 23 | 60.3% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 162 | 151 | 11 | 93.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 22 | 16 | 6 | 72.7% |
| vless | 294 | 221 | 73 | 75.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 26 |
| 204:TimeoutError | 23 |
| geo:ClientOSError | 22 |
| cn-block:TimeoutError | 20 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 6 |
| 204:ProxyConnectionError | 4 |
| geo:ProxyError | 2 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| speed:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5131 |
| ConnectionRefusedError | 882 |
| gaierror | 365 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | prefer | 248 | 0.887 | 1749 |
| mheidari-all | 0.883 | prefer | 64 | 0.812 | 16452 |
| Surfboard-tg-mixed | 0.82 | prefer | 175 | 0.743 | 7479 |
| ermaozi-get_subscribe | 0.618 | observe | 19 | 0.632 | 473 |
| ermaozi | 0.613 | observe | 40 | 0.6 | 442 |
| DeltaKronecker-all | 0.372 | observe | 9 | 0.444 | 5187 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 180 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4795 |
| Epodonios-all | 0.255 | observe | 0 | None | 7926 |

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
| DeltaKronecker-all | 0.444 | 4 | 5 | 9 |
| ermaozi | 0.6 | 24 | 16 | 40 |
| ermaozi-get_subscribe | 0.632 | 12 | 7 | 19 |
| Surfboard-tg-mixed | 0.743 | 130 | 45 | 175 |
| mheidari-all | 0.812 | 52 | 12 | 64 |
| Au1rxx-base64 | 0.887 | 220 | 28 | 248 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16452 | yes | 4.89 | 0 |
| SoliSpirit-all | 9096 | yes | 6.94 | 0 |
| Epodonios-all | 7926 | yes | 5.39 | 0 |
| Surfboard-tg-mixed | 7479 | yes | 4.42 | 0 |
| barry-far-vless | 6404 | yes | 2.25 | 0 |
| Surfboard-tg-vless | 6181 | yes | 6.38 | 0 |
| DeltaKronecker-all | 5187 | yes | 4.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 1.92 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 0.14 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 53 |
| cn-block | 27 |
| geo | 26 |
| speed | 8 |
