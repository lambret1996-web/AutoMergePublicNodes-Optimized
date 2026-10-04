# AutoNodes 每日报告

生成时间：2026-10-04 16:46:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 99556 |
| 去重后节点数 | 27321 |
| TCP 可达数 | 3000 |
| 真测通过数 | 433 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27321 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 80.3 |
| geo | 1.2 |
| probe | 331.1 |
| real_test | 200.3 |
| tcp | 47.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 5 | 0 | 100.0% |
| http | 25 | 23 | 2 | 92.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 152 | 130 | 22 | 85.5% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 109 | 77 | 32 | 70.6% |
| vless | 226 | 182 | 44 | 80.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 41 |
| cn-block:TimeoutError | 27 |
| speed:TimeoutError | 7 |
| geo:TimeoutError | 7 |
| 204:ProxyError | 6 |
| cn-block:ProxyError | 4 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 4 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6729 |
| ConnectionRefusedError | 1050 |
| gaierror | 333 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | prefer | 303 | 0.901 | 1831 |
| ermaozi | 0.915 | prefer | 25 | 0.92 | 653 |
| mheidari-all | 0.85 | prefer | 59 | 0.78 | 23366 |
| Surfboard-tg-mixed | 0.723 | prefer | 127 | 0.646 | 7225 |
| ermaozi-get_subscribe | 0.379 | observe | 3 | 1.0 | 518 |
| DeltaKronecker-all | 0.318 | observe | 17 | 0.235 | 5267 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5173 |
| Epodonios-all | 0.255 | observe | 0 | None | 7759 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.235 | 4 | 13 | 17 |
| Surfboard-tg-mixed | 0.646 | 82 | 45 | 127 |
| mheidari-all | 0.78 | 46 | 13 | 59 |
| Au1rxx-base64 | 0.901 | 273 | 30 | 303 |
| ermaozi | 0.92 | 23 | 2 | 25 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23366 | yes | 3.79 | 0 |
| SoliSpirit-all | 9833 | yes | 2.71 | 0 |
| Epodonios-all | 7759 | yes | 1.96 | 0 |
| Surfboard-tg-mixed | 7225 | yes | 2.55 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.16 | 0 |
| barry-far-vless | 6063 | yes | 0.61 | 0 |
| Surfboard-tg-vless | 5815 | yes | 2.24 | 0 |
| DeltaKronecker-all | 5267 | yes | 3.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 5173 | yes | 1.71 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 1.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 51 |
| cn-block | 35 |
| geo | 11 |
| speed | 8 |
