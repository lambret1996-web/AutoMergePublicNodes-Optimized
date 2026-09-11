# AutoNodes 每日报告

生成时间：2026-09-11 18:29:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83682 |
| 去重后节点数 | 23281 |
| TCP 可达数 | 3000 |
| 真测通过数 | 370 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23281 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 84.2 |
| geo | 1.5 |
| probe | 226.6 |
| real_test | 201.8 |
| tcp | 40.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 21 | 7 | 14 | 33.3% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 149 | 138 | 11 | 92.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 27 | 20 | 7 | 74.1% |
| vless | 259 | 183 | 76 | 70.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 26 |
| cn-block:TimeoutError | 21 |
| speed:ClientOSError | 13 |
| 204:TimeoutError | 12 |
| 204:ProxyError | 11 |
| cn-block:ClientOSError | 9 |
| 204:ProxyConnectionError | 7 |
| geo:TimeoutError | 5 |
| geo:ProxyError | 2 |
| speed:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5520 |
| ConnectionRefusedError | 901 |
| gaierror | 508 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.916 | prefer | 263 | 0.848 | 1757 |
| Surfboard-tg-mixed | 0.821 | prefer | 110 | 0.745 | 7370 |
| DeltaKronecker-all | 0.774 | prefer | 34 | 0.706 | 6070 |
| mheidari-all | 0.734 | prefer | 50 | 0.66 | 15494 |
| ermaozi | 0.418 | observe | 14 | 0.5 | 377 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7830 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8523 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5979 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.144 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| ermaozi | 0.5 | 7 | 7 | 14 |
| mheidari-all | 0.66 | 33 | 17 | 50 |
| DeltaKronecker-all | 0.706 | 24 | 10 | 34 |
| Surfboard-tg-mixed | 0.745 | 82 | 28 | 110 |
| Au1rxx-base64 | 0.848 | 223 | 40 | 263 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15494 | yes | 5.29 | 0 |
| SoliSpirit-all | 8523 | yes | 4.4 | 0 |
| Epodonios-all | 7830 | yes | 3.54 | 0 |
| Surfboard-tg-mixed | 7370 | yes | 4.5 | 0 |
| barry-far-vless | 6192 | yes | 4.4 | 0 |
| DeltaKronecker-all | 6070 | yes | 5.67 | 0 |
| Surfboard-tg-vless | 5979 | yes | 4.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 3.43 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 1.46 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.65 | 0 |

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
| geo | 33 |
| 204 | 31 |
| cn-block | 31 |
| speed | 15 |
