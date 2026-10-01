# AutoNodes 每日报告

生成时间：2026-10-01 07:10:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97940 |
| 去重后节点数 | 27098 |
| TCP 可达数 | 3000 |
| 真测通过数 | 382 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27098 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 80.3 |
| geo | 1.7 |
| probe | 264.3 |
| real_test | 270.5 |
| tcp | 46.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 4 | 0 | 100.0% |
| http | 25 | 22 | 3 | 88.0% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 163 | 144 | 19 | 88.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 22 | 16 | 6 | 72.7% |
| vless | 389 | 184 | 205 | 47.3% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 69 |
| speed:ClientOSError | 55 |
| speed:TimeoutError | 35 |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 18 |
| geo:ClientOSError | 17 |
| cn-block:ClientOSError | 9 |
| 204:ClientOSError | 4 |
| 204:ProxyConnectionError | 3 |
| 204:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6571 |
| ConnectionRefusedError | 1007 |
| gaierror | 345 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.871 | prefer | 303 | 0.805 | 1699 |
| ermaozi | 0.831 | prefer | 24 | 0.833 | 588 |
| Surfboard-tg-mixed | 0.59 | observe | 143 | 0.51 | 7136 |
| mheidari-all | 0.362 | observe | 140 | 0.279 | 22835 |
| ermaozi-get_subscribe | 0.331 | observe | 2 | 1.0 | 487 |
| tg-oneclickvpnkeys | 0.314 | observe | 2 | 1.0 | 66 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 5434 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5324 |
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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.279 | 39 | 101 | 140 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.51 | 73 | 70 | 143 |
| Au1rxx-base64 | 0.805 | 244 | 59 | 303 |
| ermaozi | 0.833 | 20 | 4 | 24 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22835 | yes | 6.72 | 0 |
| SoliSpirit-all | 9403 | yes | 2.32 | 0 |
| Epodonios-all | 7625 | yes | 3.19 | 0 |
| Surfboard-tg-mixed | 7136 | yes | 3.81 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.03 | 0 |
| barry-far-vless | 6050 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 5815 | yes | 4.18 | 0 |
| DeltaKronecker-all | 5434 | yes | 5.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 0.69 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 2.92 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 90 |
| geo | 86 |
| 204 | 34 |
| cn-block | 27 |
