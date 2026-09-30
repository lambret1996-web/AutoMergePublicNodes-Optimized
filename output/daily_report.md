# AutoNodes 每日报告

生成时间：2026-09-30 22:15:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97982 |
| 去重后节点数 | 27241 |
| TCP 可达数 | 3000 |
| 真测通过数 | 350 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27241 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 74.7 |
| geo | 1.6 |
| probe | 172.1 |
| real_test | 116.8 |
| tcp | 45.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 16 | 8 | 66.7% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 122 | 117 | 5 | 95.9% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 18 | 16 | 2 | 88.9% |
| vless | 257 | 181 | 76 | 70.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 45 |
| cn-block:TimeoutError | 13 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 5 |
| geo:ClientOSError | 4 |
| speed:TimeoutError | 4 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 3 |
| 204:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6269 |
| ConnectionRefusedError | 1015 |
| gaierror | 478 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.876 | prefer | 96 | 0.802 | 22901 |
| Au1rxx-base64 | 0.87 | prefer | 304 | 0.799 | 1803 |
| zhangkai | 0.646 | observe | 15 | 0.8 | 144 |
| Surfboard-tg-mixed | 0.606 | observe | 9 | 0.889 | 7200 |
| DeltaKronecker-all | 0.446 | observe | 8 | 0.625 | 5434 |
| ermaozi-get_subscribe | 0.307 | observe | 9 | 0.444 | 362 |
| tg-oneclickvpnkeys | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7696 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.444 | 4 | 5 | 9 |
| DeltaKronecker-all | 0.625 | 5 | 3 | 8 |
| Au1rxx-base64 | 0.799 | 243 | 61 | 304 |
| zhangkai | 0.8 | 12 | 3 | 15 |
| mheidari-all | 0.802 | 77 | 19 | 96 |
| Surfboard-tg-mixed | 0.889 | 8 | 1 | 9 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22901 | yes | 6.09 | 0 |
| SoliSpirit-all | 9724 | yes | 5.12 | 0 |
| Epodonios-all | 7696 | yes | 5.45 | 0 |
| Surfboard-tg-mixed | 7200 | yes | 3.68 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.39 | 0 |
| barry-far-vless | 6072 | yes | 1.37 | 0 |
| Surfboard-tg-vless | 5833 | yes | 5.15 | 0 |
| DeltaKronecker-all | 5434 | yes | 6.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.65 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 2.59 | 0 |

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
| speed | 49 |
| cn-block | 21 |
| 204 | 17 |
| geo | 6 |
