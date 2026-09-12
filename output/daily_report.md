# AutoNodes 每日报告

生成时间：2026-09-12 06:33:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83310 |
| 去重后节点数 | 22807 |
| TCP 可达数 | 3000 |
| 真测通过数 | 500 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22807 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 79.1 |
| geo | 1.4 |
| probe | 293.6 |
| real_test | 362.6 |
| tcp | 37.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 47 | 25 | 22 | 53.2% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 169 | 159 | 10 | 94.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 24 | 17 | 7 | 70.8% |
| vless | 535 | 285 | 250 | 53.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 101 |
| geo:ClientOSError | 57 |
| speed:ClientOSError | 32 |
| 204:ProxyError | 27 |
| speed:TimeoutError | 22 |
| cn-block:ClientOSError | 15 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 10 |
| 204:ClientOSError | 5 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 2 |
| 204:ServerDisconnectedError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4634 |
| ConnectionRefusedError | 902 |
| gaierror | 470 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.925 | prefer | 294 | 0.861 | 1683 |
| Surfboard-tg-mixed | 0.805 | prefer | 140 | 0.729 | 7232 |
| mheidari-all | 0.714 | prefer | 99 | 0.636 | 15597 |
| ermaozi | 0.617 | observe | 33 | 0.606 | 434 |
| DeltaKronecker-all | 0.356 | observe | 208 | 0.274 | 6070 |
| ermaozi-get_subscribe | 0.283 | observe | 12 | 0.333 | 459 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7720 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8713 |

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
| Surfboard-tg-vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.274 | 57 | 151 | 208 |
| ermaozi-get_subscribe | 0.333 | 4 | 8 | 12 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.606 | 20 | 13 | 33 |
| mheidari-all | 0.636 | 63 | 36 | 99 |
| Surfboard-tg-mixed | 0.729 | 102 | 38 | 140 |
| Au1rxx-base64 | 0.861 | 253 | 41 | 294 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15597 | yes | 4.74 | 0 |
| SoliSpirit-all | 8713 | yes | 2.64 | 0 |
| Epodonios-all | 7720 | yes | 4.95 | 0 |
| Surfboard-tg-mixed | 7232 | yes | 4.32 | 0 |
| barry-far-vless | 6107 | yes | 1.32 | 0 |
| DeltaKronecker-all | 6070 | yes | 5.73 | 0 |
| Surfboard-tg-vless | 5899 | yes | 5.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 1.1 | 0 |
| mahdibland-V2RayAggregator | 4207 | yes | 3.34 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.44 | 0 |

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
| geo | 158 |
| speed | 55 |
| 204 | 46 |
| cn-block | 32 |
