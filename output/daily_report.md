# AutoNodes 每日报告

生成时间：2026-09-19 00:34:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 84075 |
| 去重后节点数 | 23209 |
| TCP 可达数 | 3000 |
| 真测通过数 | 550 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23209 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 25.9 |
| geo | 1.4 |
| probe | 253.5 |
| real_test | 329.4 |
| tcp | 39.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 32 | 21 | 11 | 65.6% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 176 | 165 | 11 | 93.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 44 | 31 | 13 | 70.5% |
| vless | 512 | 312 | 200 | 60.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 87 |
| speed:TimeoutError | 51 |
| geo:ClientOSError | 27 |
| speed:ClientOSError | 20 |
| 204:ProxyError | 13 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 13 |
| 204:TimeoutError | 7 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5595 |
| ConnectionRefusedError | 815 |
| gaierror | 284 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | prefer | 319 | 0.906 | 1773 |
| ermaozi | 0.821 | prefer | 24 | 0.833 | 325 |
| Surfboard-tg-mixed | 0.743 | prefer | 244 | 0.664 | 7329 |
| mheidari-all | 0.553 | observe | 129 | 0.473 | 15908 |
| roosterkid-openproxylist-v2ray | 0.483 | observe | 6 | 1.0 | 150 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| DeltaKronecker-all | 0.269 | observe | 51 | 0.176 | 6040 |
| Epodonios-all | 0.255 | observe | 0 | None | 7793 |
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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.136 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.125 | 1 | 7 | 8 |
| DeltaKronecker-all | 0.176 | 9 | 42 | 51 |
| mheidari-all | 0.473 | 61 | 68 | 129 |
| Surfboard-tg-mixed | 0.664 | 162 | 82 | 244 |
| ermaozi | 0.833 | 20 | 4 | 24 |
| Au1rxx-base64 | 0.906 | 289 | 30 | 319 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15908 | yes | 2.52 | 0 |
| SoliSpirit-all | 8782 | yes | 1.41 | 0 |
| Epodonios-all | 7793 | yes | 1.6 | 0 |
| Surfboard-tg-mixed | 7329 | yes | 1.72 | 0 |
| barry-far-vless | 6111 | yes | 28.06 | 0 |
| DeltaKronecker-all | 6040 | yes | 2.79 | 0 |
| Surfboard-tg-vless | 5896 | yes | 1.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 0.77 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 1.42 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.6 | 0 |

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
| geo | 114 |
| speed | 72 |
| cn-block | 28 |
| 204 | 23 |
