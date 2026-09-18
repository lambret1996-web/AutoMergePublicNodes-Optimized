# AutoNodes 每日报告

生成时间：2026-09-18 18:31:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 86644 |
| 去重后节点数 | 25073 |
| TCP 可达数 | 3000 |
| 真测通过数 | 416 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25073 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 16.6 |
| generate | 92.8 |
| geo | 1.5 |
| probe | 327.3 |
| real_test | 259.6 |
| tcp | 41.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 33 | 22 | 11 | 66.7% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 163 | 140 | 23 | 85.9% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 9 | 7 | 2 | 77.8% |
| vless | 365 | 227 | 138 | 62.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 43 |
| cn-block:ClientOSError | 28 |
| 204:ProxyError | 23 |
| 204:TimeoutError | 22 |
| speed:ClientOSError | 17 |
| geo:TimeoutError | 15 |
| cn-block:TimeoutError | 14 |
| speed:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| speed:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5845 |
| ConnectionRefusedError | 902 |
| gaierror | 392 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.912 | prefer | 282 | 0.851 | 1594 |
| ermaozi | 0.828 | prefer | 25 | 0.84 | 325 |
| Surfboard-tg-mixed | 0.71 | prefer | 98 | 0.633 | 7175 |
| mheidari-all | 0.618 | observe | 169 | 0.538 | 19611 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5076 |
| Epodonios-all | 0.255 | observe | 0 | None | 7628 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8673 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5700 |

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
| downweight | ermaozi-get_subscribe | 0.136 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.144 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 7 | 7 |
| ermaozi-get_subscribe | 0.125 | 1 | 7 | 8 |
| mheidari-all | 0.538 | 91 | 78 | 169 |
| Surfboard-tg-mixed | 0.633 | 62 | 36 | 98 |
| ermaozi | 0.84 | 21 | 4 | 25 |
| Au1rxx-base64 | 0.851 | 240 | 42 | 282 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19611 | yes | 16.87 | 0 |
| SoliSpirit-all | 8673 | yes | 1.8 | 0 |
| Epodonios-all | 7628 | yes | 17.17 | 0 |
| Surfboard-tg-mixed | 7175 | yes | 2.99 | 0 |
| DeltaKronecker-all | 6040 | yes | 3.29 | 0 |
| barry-far-vless | 5915 | yes | 0.86 | 0 |
| Surfboard-tg-vless | 5700 | yes | 3.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 0.66 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 2.62 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.97 | 0 |

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
| geo | 58 |
| 204 | 51 |
| cn-block | 44 |
| speed | 23 |
