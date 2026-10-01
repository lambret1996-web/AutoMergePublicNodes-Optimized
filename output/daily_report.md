# AutoNodes 每日报告

生成时间：2026-10-01 18:18:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 98761 |
| 去重后节点数 | 27523 |
| TCP 可达数 | 3000 |
| 真测通过数 | 179 |
| verified 输出数 | 179 |
| global 输出数 | 186 |
| all 输出数 | 27523 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 94.5 |
| geo | 1.5 |
| probe | 229.7 |
| real_test | 111.8 |
| tcp | 45.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 17 | 5 | 77.3% |
| hysteria2 | 23 | 21 | 2 | 91.3% |
| shadowsocks | 136 | 114 | 22 | 83.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 13 | 9 | 4 | 69.2% |
| vless | 32 | 17 | 15 | 53.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 10 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 4 |
| 204:ProxyConnectionError | 3 |
| speed:TimeoutError | 3 |
| geo:TimeoutError | 3 |
| speed:ClientOSError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6042 |
| ConnectionRefusedError | 1035 |
| gaierror | 417 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 95 | 0.937 | 1825 |
| Surfboard-tg-mixed | 0.886 | prefer | 29 | 0.828 | 7228 |
| zhangkai | 0.788 | prefer | 21 | 0.81 | 144 |
| mheidari-all | 0.7 | prefer | 77 | 0.623 | 23055 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 5603 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5324 |
| Epodonios-all | 0.255 | observe | 0 | None | 7640 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9977 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5857 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.623 | 48 | 29 | 77 |
| zhangkai | 0.81 | 17 | 4 | 21 |
| Surfboard-tg-mixed | 0.828 | 24 | 5 | 29 |
| Au1rxx-base64 | 0.937 | 89 | 6 | 95 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23055 | yes | 6.78 | 0 |
| SoliSpirit-all | 9977 | yes | 3.7 | 0 |
| Epodonios-all | 7640 | yes | 3.72 | 0 |
| Surfboard-tg-mixed | 7228 | yes | 4.23 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.18 | 0 |
| barry-far-vless | 6032 | yes | 1.54 | 0 |
| Surfboard-tg-vless | 5857 | yes | 3.99 | 0 |
| DeltaKronecker-all | 5603 | yes | 4.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 2.34 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 3.37 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| real_ok_drop_50pct | real-test ok dropped from 430 to 179 |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 32 |
| cn-block | 10 |
| speed | 4 |
| geo | 4 |
