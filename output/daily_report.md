# AutoNodes 每日报告

生成时间：2026-09-29 22:16:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96969 |
| 去重后节点数 | 27167 |
| TCP 可达数 | 3000 |
| 真测通过数 | 359 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27167 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 47.2 |
| geo | 1.5 |
| probe | 208.0 |
| real_test | 129.2 |
| tcp | 44.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 26 | 22 | 4 | 84.6% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 113 | 109 | 4 | 96.5% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 7 | 5 | 2 | 71.4% |
| vless | 254 | 195 | 59 | 76.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 25 |
| cn-block:TimeoutError | 17 |
| speed:TimeoutError | 6 |
| 204:TimeoutError | 6 |
| 204:ProxyError | 5 |
| geo:TimeoutError | 5 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 2 |
| 204:ProxyConnectionError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5619 |
| ConnectionRefusedError | 1023 |
| gaierror | 395 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.914 | prefer | 270 | 0.844 | 1792 |
| mheidari-all | 0.896 | prefer | 112 | 0.821 | 22763 |
| ermaozi | 0.826 | prefer | 25 | 0.84 | 291 |
| DeltaKronecker-all | 0.489 | observe | 9 | 0.667 | 5528 |
| Surfboard-tg-mixed | 0.489 | observe | 6 | 0.833 | 7082 |
| ermaozi-get_subscribe | 0.37 | observe | 3 | 1.0 | 293 |
| tg-oneclickvpnkeys | 0.36 | observe | 3 | 1.0 | 62 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5314 |
| Epodonios-all | 0.255 | observe | 0 | None | 7556 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.667 | 6 | 3 | 9 |
| mheidari-all | 0.821 | 92 | 20 | 112 |
| Surfboard-tg-mixed | 0.833 | 5 | 1 | 6 |
| ermaozi | 0.84 | 21 | 4 | 25 |
| Au1rxx-base64 | 0.844 | 228 | 42 | 270 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |
| ermaozi-get_subscribe | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22763 | yes | 6.44 | 0 |
| SoliSpirit-all | 9172 | yes | 3.56 | 0 |
| Epodonios-all | 7556 | yes | 3.23 | 0 |
| Surfboard-tg-mixed | 7082 | yes | 5.23 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.91 | 0 |
| barry-far-vless | 5942 | yes | 2.3 | 0 |
| Surfboard-tg-vless | 5695 | yes | 3.69 | 0 |
| DeltaKronecker-all | 5528 | yes | 5.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 5314 | yes | 1.99 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 2.06 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 31 |
| cn-block | 22 |
| 204 | 13 |
| geo | 6 |
