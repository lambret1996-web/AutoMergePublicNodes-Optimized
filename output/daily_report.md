# AutoNodes 每日报告

生成时间：2026-10-10 17:18:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98017 |
| 去重后节点数 | 27210 |
| TCP 可达数 | 3000 |
| 真测通过数 | 461 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27210 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 77.4 |
| geo | 1.6 |
| probe | 351.9 |
| real_test | 344.7 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 1 | 3 | 25.0% |
| http | 52 | 26 | 26 | 50.0% |
| hysteria2 | 22 | 18 | 4 | 81.8% |
| shadowsocks | 159 | 129 | 30 | 81.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 123 | 109 | 14 | 88.6% |
| vless | 246 | 176 | 70 | 71.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 34 |
| 204:TimeoutError | 33 |
| 204:ProxyError | 31 |
| geo:ClientOSError | 14 |
| 204:ClientOSError | 10 |
| speed:ClientOSError | 9 |
| speed:TimeoutError | 8 |
| cn-block:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6565 |
| ConnectionRefusedError | 1024 |
| gaierror | 349 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.931 | prefer | 374 | 0.858 | 1857 |
| mheidari-all | 0.807 | prefer | 53 | 0.736 | 23714 |
| Surfboard-tg-mixed | 0.673 | observe | 121 | 0.595 | 7171 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 174 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7647 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9352 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.166 | 33 | 0.121 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.121 | 4 | 29 | 33 |
| Surfboard-tg-mixed | 0.595 | 72 | 49 | 121 |
| mheidari-all | 0.736 | 39 | 14 | 53 |
| Au1rxx-base64 | 0.858 | 321 | 53 | 374 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23714 | yes | 4.04 | 0 |
| SoliSpirit-all | 9352 | yes | 3.73 | 0 |
| Epodonios-all | 7647 | yes | 2.42 | 0 |
| Surfboard-tg-mixed | 7171 | yes | 3.04 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.81 | 0 |
| barry-far-vless | 5914 | yes | 2.11 | 0 |
| Surfboard-tg-vless | 5676 | yes | 2.81 | 0 |
| DeltaKronecker-all | 5009 | yes | 4.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4999 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 4347 | yes | 1.03 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 74 |
| cn-block | 40 |
| geo | 18 |
| speed | 17 |
