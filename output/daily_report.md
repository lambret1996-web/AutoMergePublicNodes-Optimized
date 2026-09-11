# AutoNodes 每日报告

生成时间：2026-09-11 12:32:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84160 |
| 去重后节点数 | 23261 |
| TCP 可达数 | 3000 |
| 真测通过数 | 435 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23261 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 75.8 |
| geo | 1.4 |
| probe | 225.0 |
| real_test | 272.4 |
| tcp | 40.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 43 | 31 | 12 | 72.1% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 160 | 143 | 17 | 89.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 30 | 28 | 2 | 93.3% |
| vless | 288 | 212 | 76 | 73.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 33 |
| speed:TimeoutError | 13 |
| cn-block:TimeoutError | 13 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 9 |
| 204:TimeoutError | 8 |
| speed:ClientOSError | 7 |
| geo:TimeoutError | 7 |
| 204:ClientOSError | 3 |
| 204:ProxyConnectionError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5584 |
| ConnectionRefusedError | 889 |
| gaierror | 433 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.949 | prefer | 268 | 0.881 | 1774 |
| Surfboard-tg-mixed | 0.937 | prefer | 103 | 0.864 | 7422 |
| ermaozi | 0.722 | prefer | 42 | 0.714 | 431 |
| mheidari-all | 0.716 | prefer | 53 | 0.642 | 15701 |
| DeltaKronecker-all | 0.686 | observe | 69 | 0.609 | 6070 |
| ermaozi-get_subscribe | 0.273 | observe | 1 | 1.0 | 461 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 199 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7889 |
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
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.5 | 2 | 2 | 4 |
| DeltaKronecker-all | 0.609 | 42 | 27 | 69 |
| mheidari-all | 0.642 | 34 | 19 | 53 |
| ermaozi | 0.714 | 30 | 12 | 42 |
| Surfboard-tg-mixed | 0.864 | 89 | 14 | 103 |
| Au1rxx-base64 | 0.881 | 236 | 32 | 268 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15701 | yes | 3.88 | 0 |
| SoliSpirit-all | 8530 | yes | 3.01 | 0 |
| Epodonios-all | 7889 | yes | 2.56 | 0 |
| Surfboard-tg-mixed | 7422 | yes | 3.57 | 0 |
| barry-far-vless | 6213 | yes | 1.79 | 0 |
| DeltaKronecker-all | 6070 | yes | 4.21 | 0 |
| Surfboard-tg-vless | 5995 | yes | 3.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 1.95 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 1.26 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.62 | 0 |

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
| geo | 42 |
| 204 | 23 |
| cn-block | 22 |
| speed | 21 |
