# AutoNodes 每日报告

生成时间：2026-09-24 00:43:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96715 |
| 去重后节点数 | 26644 |
| TCP 可达数 | 3000 |
| 真测通过数 | 562 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26644 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 80.6 |
| geo | 1.6 |
| probe | 394.7 |
| real_test | 677.0 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 34 | 24 | 10 | 70.6% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 167 | 162 | 5 | 97.0% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 19 | 10 | 9 | 52.6% |
| vless | 924 | 343 | 581 | 37.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 266 |
| speed:TimeoutError | 130 |
| geo:ClientOSError | 60 |
| speed:ClientOSError | 54 |
| cn-block:ClientOSError | 41 |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 15 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5724 |
| ConnectionRefusedError | 988 |
| gaierror | 457 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | prefer | 267 | 0.895 | 1634 |
| ermaozi | 0.793 | prefer | 30 | 0.8 | 291 |
| Surfboard-tg-mixed | 0.774 | prefer | 70 | 0.7 | 7099 |
| mheidari-all | 0.393 | observe | 781 | 0.312 | 22311 |
| roosterkid-openproxylist-v2ray | 0.317 | observe | 2 | 1.0 | 149 |
| DeltaKronecker-all | 0.298 | observe | 11 | 0.273 | 6471 |
| Epodonios-all | 0.255 | observe | 0 | None | 7561 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8878 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5729 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.159 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| DeltaKronecker-all | 0.273 | 3 | 8 | 11 |
| mheidari-all | 0.312 | 244 | 537 | 781 |
| Surfboard-tg-mixed | 0.7 | 49 | 21 | 70 |
| ermaozi | 0.8 | 24 | 6 | 30 |
| Au1rxx-base64 | 0.895 | 239 | 28 | 267 |
| roosterkid-openproxylist-v2ray | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22311 | yes | 6.44 | 0 |
| SoliSpirit-all | 8878 | yes | 2.5 | 0 |
| Epodonios-all | 7561 | yes | 3.36 | 0 |
| Surfboard-tg-mixed | 7099 | yes | 3.72 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.12 | 0 |
| DeltaKronecker-all | 6471 | yes | 5.37 | 0 |
| barry-far-vless | 5948 | yes | 1.22 | 0 |
| Surfboard-tg-vless | 5729 | yes | 3.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 1.46 | 0 |
| mahdibland-V2RayAggregator | 4332 | yes | 3.06 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 326 |
| speed | 184 |
| cn-block | 61 |
| 204 | 37 |
