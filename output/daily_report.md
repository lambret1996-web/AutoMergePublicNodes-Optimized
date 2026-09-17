# AutoNodes 每日报告

生成时间：2026-09-17 18:29:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 84303 |
| 去重后节点数 | 23020 |
| TCP 可达数 | 3000 |
| 真测通过数 | 384 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23020 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 91.1 |
| geo | 1.4 |
| probe | 217.5 |
| real_test | 215.8 |
| tcp | 37.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 37 | 24 | 13 | 64.9% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 153 | 134 | 19 | 87.6% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 21 | 9 | 12 | 42.9% |
| vless | 276 | 197 | 79 | 71.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 31 |
| 204:ProxyError | 22 |
| geo:ClientOSError | 15 |
| geo:TimeoutError | 14 |
| speed:ClientOSError | 13 |
| cn-block:TimeoutError | 11 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:47988: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4945 |
| ConnectionRefusedError | 844 |
| gaierror | 477 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | prefer | 263 | 0.882 | 1620 |
| mheidari-all | 0.712 | prefer | 55 | 0.636 | 15839 |
| ermaozi | 0.711 | prefer | 31 | 0.71 | 357 |
| Surfboard-tg-mixed | 0.683 | observe | 124 | 0.605 | 7430 |
| DeltaKronecker-all | 0.628 | observe | 29 | 0.552 | 5931 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4261 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5093 |
| Epodonios-all | 0.255 | observe | 0 | None | 7888 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9061 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.234 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.552 | 16 | 13 | 29 |
| Surfboard-tg-mixed | 0.605 | 75 | 49 | 124 |
| mheidari-all | 0.636 | 35 | 20 | 55 |
| ermaozi | 0.71 | 22 | 9 | 31 |
| Au1rxx-base64 | 0.882 | 232 | 31 | 263 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15839 | yes | 4.71 | 0 |
| SoliSpirit-all | 9061 | yes | 2.2 | 0 |
| Epodonios-all | 7888 | yes | 5.72 | 0 |
| Surfboard-tg-mixed | 7430 | yes | 3.72 | 0 |
| barry-far-vless | 6129 | yes | 1.39 | 0 |
| DeltaKronecker-all | 5931 | yes | 4.94 | 0 |
| Surfboard-tg-vless | 5904 | yes | 3.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 1.05 | 0 |
| mahdibland-V2RayAggregator | 4261 | yes | 3.14 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 61 |
| geo | 29 |
| cn-block | 18 |
| speed | 18 |
| sing-box exited 1 | 1 |
