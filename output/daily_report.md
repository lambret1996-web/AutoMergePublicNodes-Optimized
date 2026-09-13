# AutoNodes 每日报告

生成时间：2026-09-13 12:30:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 94187 |
| 去重后节点数 | 25223 |
| TCP 可达数 | 3000 |
| 真测通过数 | 433 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25223 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 95.4 |
| geo | 1.4 |
| probe | 228.8 |
| real_test | 216.7 |
| tcp | 41.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 39 | 22 | 17 | 56.4% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 165 | 152 | 13 | 92.1% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 28 | 26 | 2 | 92.9% |
| vless | 364 | 210 | 154 | 57.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 58 |
| cn-block:ClientOSError | 39 |
| speed:ClientOSError | 26 |
| 204:ProxyError | 23 |
| cn-block:TimeoutError | 14 |
| 204:TimeoutError | 11 |
| geo:TimeoutError | 8 |
| speed:TimeoutError | 6 |
| geo:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5293 |
| ConnectionRefusedError | 982 |
| gaierror | 560 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.948 | prefer | 89 | 0.876 | 7439 |
| Au1rxx-base64 | 0.887 | prefer | 278 | 0.824 | 1633 |
| ermaozi | 0.638 | observe | 27 | 0.63 | 436 |
| mheidari-all | 0.566 | observe | 214 | 0.486 | 20485 |
| ermaozi-get_subscribe | 0.328 | observe | 13 | 0.385 | 464 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| Epodonios-all | 0.255 | observe | 0 | None | 7887 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8929 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6075 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.385 | 5 | 8 | 13 |
| mheidari-all | 0.486 | 104 | 110 | 214 |
| ermaozi | 0.63 | 17 | 10 | 27 |
| Au1rxx-base64 | 0.824 | 229 | 49 | 278 |
| Surfboard-tg-mixed | 0.876 | 78 | 11 | 89 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20485 | yes | 5.92 | 0 |
| SoliSpirit-all | 8929 | yes | 4.58 | 0 |
| Epodonios-all | 7887 | yes | 1.9 | 0 |
| Surfboard-tg-mixed | 7439 | yes | 3.81 | 0 |
| barry-far-vless | 6291 | yes | 2.47 | 0 |
| Surfboard-tg-vless | 6075 | yes | 4.6 | 0 |
| DeltaKronecker-all | 5892 | yes | 6.55 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 3.65 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 2.7 | 0 |
| mahdibland-V2RayAggregator | 4221 | yes | 0.71 | 0 |

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
| geo | 68 |
| cn-block | 54 |
| 204 | 36 |
| speed | 33 |
