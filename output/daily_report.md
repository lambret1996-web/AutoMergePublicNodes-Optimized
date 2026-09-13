# AutoNodes 每日报告

生成时间：2026-09-13 18:28:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 95109 |
| 去重后节点数 | 25430 |
| TCP 可达数 | 3000 |
| 真测通过数 | 448 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25430 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 77.9 |
| geo | 1.4 |
| probe | 222.7 |
| real_test | 212.3 |
| tcp | 43.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 39 | 23 | 16 | 59.0% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 162 | 146 | 16 | 90.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 21 | 16 | 5 | 76.2% |
| vless | 406 | 237 | 169 | 58.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 66 |
| cn-block:ClientOSError | 44 |
| speed:ClientOSError | 30 |
| 204:ProxyError | 21 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 10 |
| speed:TimeoutError | 6 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:exit-country | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6289 |
| ConnectionRefusedError | 970 |
| gaierror | 306 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.901 | prefer | 301 | 0.834 | 1740 |
| Surfboard-tg-mixed | 0.796 | prefer | 146 | 0.719 | 7573 |
| ermaozi | 0.637 | observe | 35 | 0.629 | 382 |
| mheidari-all | 0.489 | observe | 162 | 0.407 | 20529 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4222 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5301 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| Epodonios-all | 0.255 | observe | 0 | None | 8071 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9137 |

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
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.162 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.407 | 66 | 96 | 162 |
| ermaozi | 0.629 | 22 | 13 | 35 |
| Surfboard-tg-mixed | 0.719 | 105 | 41 | 146 |
| Au1rxx-base64 | 0.834 | 251 | 50 | 301 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20529 | yes | 3.81 | 0 |
| SoliSpirit-all | 9137 | yes | 2.93 | 0 |
| Epodonios-all | 8071 | yes | 3.97 | 0 |
| Surfboard-tg-mixed | 7573 | yes | 3.07 | 0 |
| barry-far-vless | 6393 | yes | 3.95 | 0 |
| Surfboard-tg-vless | 6175 | yes | 4.14 | 0 |
| DeltaKronecker-all | 5892 | yes | 5.38 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 4.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 2.37 | 0 |
| mahdibland-V2RayAggregator | 4222 | yes | 1.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 72 |
| cn-block | 56 |
| 204 | 44 |
| speed | 36 |
