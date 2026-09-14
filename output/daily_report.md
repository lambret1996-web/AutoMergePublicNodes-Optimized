# AutoNodes 每日报告

生成时间：2026-09-14 12:32:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84799 |
| 去重后节点数 | 23007 |
| TCP 可达数 | 3000 |
| 真测通过数 | 444 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23007 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 75.2 |
| geo | 1.5 |
| probe | 228.8 |
| real_test | 202.6 |
| tcp | 38.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 68 | 47 | 21 | 69.1% |
| hysteria2 | 16 | 13 | 3 | 81.2% |
| shadowsocks | 154 | 149 | 5 | 96.8% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 18 | 15 | 3 | 83.3% |
| vless | 313 | 219 | 94 | 70.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 34 |
| 204:ProxyError | 22 |
| speed:ClientOSError | 17 |
| cn-block:ClientOSError | 12 |
| cn-block:TimeoutError | 12 |
| geo:TimeoutError | 10 |
| 204:TimeoutError | 8 |
| speed:TimeoutError | 7 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40774: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5123 |
| ConnectionRefusedError | 871 |
| gaierror | 395 |
| OSError | 14 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.946 | prefer | 288 | 0.882 | 1668 |
| Surfboard-tg-mixed | 0.793 | prefer | 113 | 0.717 | 7478 |
| mheidari-all | 0.789 | prefer | 53 | 0.717 | 15903 |
| ermaozi | 0.728 | prefer | 50 | 0.72 | 417 |
| ermaozi-get_subscribe | 0.579 | observe | 18 | 0.611 | 444 |
| DeltaKronecker-all | 0.57 | observe | 47 | 0.489 | 5972 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 131 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4914 |
| Epodonios-all | 0.255 | observe | 0 | None | 7910 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.489 | 23 | 24 | 47 |
| ermaozi-get_subscribe | 0.611 | 11 | 7 | 18 |
| mheidari-all | 0.717 | 38 | 15 | 53 |
| Surfboard-tg-mixed | 0.717 | 81 | 32 | 113 |
| ermaozi | 0.72 | 36 | 14 | 50 |
| Au1rxx-base64 | 0.882 | 254 | 34 | 288 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15903 | yes | 5.37 | 0 |
| SoliSpirit-all | 9127 | yes | 3.92 | 0 |
| Epodonios-all | 7910 | yes | 5.68 | 0 |
| Surfboard-tg-mixed | 7478 | yes | 4.25 | 0 |
| barry-far-vless | 6310 | yes | 3.13 | 0 |
| Surfboard-tg-vless | 6074 | yes | 4.97 | 0 |
| DeltaKronecker-all | 5972 | yes | 5.23 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 2.93 | 0 |
| mahdibland-V2RayAggregator | 4176 | yes | 3.26 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.55 | 0 |

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
| geo | 44 |
| 204 | 31 |
| cn-block | 27 |
| speed | 24 |
| sing-box exited 1 | 1 |
