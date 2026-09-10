# AutoNodes 每日报告

生成时间：2026-09-10 18:30:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 89661 |
| 去重后节点数 | 24417 |
| TCP 可达数 | 3000 |
| 真测通过数 | 386 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24417 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 85.2 |
| geo | 1.5 |
| probe | 296.7 |
| real_test | 223.1 |
| tcp | 41.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 26 | 21 | 5 | 80.8% |
| hysteria2 | 21 | 17 | 4 | 81.0% |
| shadowsocks | 131 | 122 | 9 | 93.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 11 | 6 | 5 | 54.5% |
| vless | 344 | 219 | 125 | 63.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 46 |
| cn-block:ClientOSError | 34 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 14 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 9 |
| geo:TimeoutError | 7 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 4 |
| 204:ProxyConnectionError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5667 |
| ConnectionRefusedError | 986 |
| gaierror | 463 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.92 | prefer | 272 | 0.857 | 1657 |
| ermaozi | 0.785 | prefer | 24 | 0.792 | 405 |
| Surfboard-tg-mixed | 0.775 | prefer | 80 | 0.7 | 7221 |
| mheidari-all | 0.574 | observe | 152 | 0.493 | 18727 |
| tg-oneclickvpnkeys | 0.32 | observe | 2 | 1.0 | 223 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7657 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8628 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5840 |

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
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| mheidari-all | 0.493 | 75 | 77 | 152 |
| Surfboard-tg-mixed | 0.7 | 56 | 24 | 80 |
| ermaozi | 0.792 | 19 | 5 | 24 |
| Au1rxx-base64 | 0.857 | 233 | 39 | 272 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18727 | yes | 6.87 | 0 |
| SoliSpirit-all | 8628 | yes | 2.97 | 0 |
| Epodonios-all | 7657 | yes | 3.51 | 0 |
| Surfboard-tg-mixed | 7221 | yes | 4.6 | 0 |
| barry-far-vless | 6014 | yes | 0.93 | 0 |
| DeltaKronecker-all | 5853 | yes | 5.34 | 0 |
| Surfboard-tg-vless | 5840 | yes | 4.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 0.66 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 1.52 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 55 |
| geo | 53 |
| 204 | 28 |
| speed | 13 |
