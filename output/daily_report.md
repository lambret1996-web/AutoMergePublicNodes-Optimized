# AutoNodes 每日报告

生成时间：2026-09-24 11:42:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96309 |
| 去重后节点数 | 26221 |
| TCP 可达数 | 3000 |
| 真测通过数 | 374 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26221 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 73.6 |
| geo | 1.4 |
| probe | 268.5 |
| real_test | 174.1 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 68 | 41 | 27 | 60.3% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 160 | 146 | 14 | 91.2% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 23 | 12 | 11 | 52.2% |
| vless | 257 | 153 | 104 | 59.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 38 |
| cn-block:ClientOSError | 36 |
| 204:TimeoutError | 27 |
| geo:TimeoutError | 16 |
| cn-block:TimeoutError | 15 |
| speed:TimeoutError | 15 |
| geo:ClientOSError | 6 |
| cn-block:ProxyError | 2 |
| speed:ClientOSError | 2 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6134 |
| ConnectionRefusedError | 967 |
| gaierror | 341 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | prefer | 218 | 0.881 | 1658 |
| Surfboard-tg-mixed | 0.765 | prefer | 109 | 0.688 | 7027 |
| ermaozi | 0.632 | observe | 53 | 0.623 | 339 |
| mheidari-all | 0.545 | observe | 127 | 0.465 | 22399 |
| DeltaKronecker-all | 0.507 | observe | 8 | 0.75 | 5845 |
| ermaozi-get_subscribe | 0.49 | observe | 17 | 0.529 | 373 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5307 |
| Epodonios-all | 0.255 | observe | 0 | None | 7495 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8857 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.465 | 59 | 68 | 127 |
| ermaozi-get_subscribe | 0.529 | 9 | 8 | 17 |
| ermaozi | 0.623 | 33 | 20 | 53 |
| Surfboard-tg-mixed | 0.688 | 75 | 34 | 109 |
| DeltaKronecker-all | 0.75 | 6 | 2 | 8 |
| Au1rxx-base64 | 0.881 | 192 | 26 | 218 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22399 | yes | 4.44 | 0 |
| SoliSpirit-all | 8857 | yes | 3.34 | 0 |
| Epodonios-all | 7495 | yes | 2.41 | 0 |
| Surfboard-tg-mixed | 7027 | yes | 3.6 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.35 | 0 |
| barry-far-vless | 5899 | yes | 0.87 | 0 |
| DeltaKronecker-all | 5845 | yes | 4.22 | 0 |
| Surfboard-tg-vless | 5676 | yes | 2.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 2.06 | 0 |
| mahdibland-V2RayAggregator | 4305 | yes | 2.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 66 |
| cn-block | 53 |
| geo | 23 |
| speed | 17 |
