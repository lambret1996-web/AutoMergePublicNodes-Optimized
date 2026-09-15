# AutoNodes 每日报告

生成时间：2026-09-15 18:28:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84957 |
| 去重后节点数 | 23035 |
| TCP 可达数 | 3000 |
| 真测通过数 | 456 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23035 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 95.5 |
| geo | 1.8 |
| probe | 214.4 |
| real_test | 220.4 |
| tcp | 38.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 43 | 35 | 8 | 81.4% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 155 | 142 | 13 | 91.6% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 11 | 7 | 4 | 63.6% |
| vless | 338 | 255 | 83 | 75.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 25 |
| cn-block:TimeoutError | 21 |
| cn-block:ClientOSError | 16 |
| 204:ProxyError | 13 |
| 204:TimeoutError | 11 |
| speed:ClientOSError | 8 |
| geo:TimeoutError | 6 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5197 |
| ConnectionRefusedError | 847 |
| gaierror | 394 |
| OSError | 29 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.948 | prefer | 311 | 0.887 | 1587 |
| DeltaKronecker-all | 0.933 | prefer | 32 | 0.875 | 5932 |
| ermaozi | 0.802 | prefer | 40 | 0.8 | 406 |
| mheidari-all | 0.797 | prefer | 44 | 0.727 | 15952 |
| Surfboard-tg-mixed | 0.696 | observe | 136 | 0.618 | 7516 |
| ermaozi-get_subscribe | 0.328 | observe | 2 | 1.0 | 422 |
| tg-oneclickvpnkeys | 0.318 | observe | 2 | 1.0 | 163 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 7980 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.618 | 84 | 52 | 136 |
| mheidari-all | 0.727 | 32 | 12 | 44 |
| ermaozi | 0.8 | 32 | 8 | 40 |
| DeltaKronecker-all | 0.875 | 28 | 4 | 32 |
| Au1rxx-base64 | 0.887 | 276 | 35 | 311 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15952 | yes | 3.76 | 0 |
| SoliSpirit-all | 9067 | yes | 2.74 | 0 |
| Epodonios-all | 7980 | yes | 4.46 | 0 |
| Surfboard-tg-mixed | 7516 | yes | 4.02 | 0 |
| barry-far-vless | 6287 | yes | 1.24 | 0 |
| Surfboard-tg-vless | 6065 | yes | 2.97 | 0 |
| DeltaKronecker-all | 5932 | yes | 4.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 0.97 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 2.25 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.04 | 0 |

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
| cn-block | 41 |
| geo | 31 |
| 204 | 28 |
| speed | 12 |
