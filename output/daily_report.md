# AutoNodes 每日报告

生成时间：2026-09-07 12:36:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 94680 |
| 去重后节点数 | 24961 |
| TCP 可达数 | 300 |
| 真测通过数 | 185 |
| verified 输出数 | 30 |
| global 输出数 | 30 |
| all 输出数 | 24961 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 45.5 |
| geo | 1.4 |
| probe | 16.3 |
| real_test | 42.8 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 54 | 38 | 16 | 70.4% |
| socks | 2 | 1 | 1 | 50.0% |
| vless | 114 | 107 | 7 | 93.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyConnectionError | 13 |
| speed:TimeoutError | 3 |
| cn-block:TimeoutError | 3 |
| 204:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| geo:TimeoutError | 1 |
| 204:ClientOSError | 1 |
| speed:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5311 |
| ConnectionRefusedError | 1028 |
| gaierror | 359 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Au1rxx-base64 | 0.939 | prefer | 179 | 0.872 | 1788 |
| mheidari-all | 0.349 | observe | 3 | 0.667 | 21631 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 7247 |
| tg-oneclickvpnkeys | 0.275 | observe | 3 | 0.667 | 151 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4650 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 6417 |
| Epodonios-all | 0.255 | observe | 0 | None | 7707 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8437 |

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
| mheidari-all | 0.667 | 2 | 1 | 3 |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.872 | 156 | 23 | 179 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21631 | yes | 5.73 | 0 |
| SoliSpirit-all | 8437 | yes | 3.66 | 0 |
| Epodonios-all | 7707 | yes | 3.37 | 0 |
| Surfboard-tg-mixed | 7247 | yes | 4.47 | 0 |
| DeltaKronecker-all | 6417 | yes | 6.01 | 0 |
| barry-far-vless | 6245 | yes | 2.19 | 0 |
| Surfboard-tg-vless | 6030 | yes | 4.68 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 2.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 2.4 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 3.03 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 300 to 30 |
| real_ok_drop_50pct | real-test ok dropped from 492 to 185 |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 16 |
| cn-block | 5 |
| speed | 4 |
| geo | 1 |
