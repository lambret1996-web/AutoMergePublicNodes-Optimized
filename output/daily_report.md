# AutoNodes 每日报告

生成时间：2026-09-23 18:29:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97372 |
| 去重后节点数 | 26673 |
| TCP 可达数 | 3000 |
| 真测通过数 | 404 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26673 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 73.4 |
| geo | 1.5 |
| probe | 194.8 |
| real_test | 164.9 |
| tcp | 43.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 35 | 23 | 12 | 65.7% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 177 | 155 | 22 | 87.6% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 16 | 10 | 6 | 62.5% |
| vless | 282 | 196 | 86 | 69.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 36 |
| cn-block:TimeoutError | 26 |
| 204:TimeoutError | 21 |
| 204:ProxyError | 17 |
| cn-block:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 4 |
| speed:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5972 |
| ConnectionRefusedError | 962 |
| gaierror | 275 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.953 | prefer | 270 | 0.889 | 1665 |
| mheidari-all | 0.769 | prefer | 101 | 0.693 | 22490 |
| ermaozi | 0.754 | prefer | 29 | 0.759 | 291 |
| Surfboard-tg-mixed | 0.648 | observe | 123 | 0.569 | 7072 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4332 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5131 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 6471 |
| Epodonios-all | 0.255 | observe | 0 | None | 7607 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9166 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.141 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| Surfboard-tg-mixed | 0.569 | 70 | 53 | 123 |
| mheidari-all | 0.693 | 70 | 31 | 101 |
| ermaozi | 0.759 | 22 | 7 | 29 |
| Au1rxx-base64 | 0.889 | 240 | 30 | 270 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22490 | yes | 5.49 | 0 |
| SoliSpirit-all | 9166 | yes | 4.28 | 0 |
| Epodonios-all | 7607 | yes | 2.72 | 0 |
| Surfboard-tg-mixed | 7072 | yes | 3.58 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.97 | 0 |
| DeltaKronecker-all | 6471 | yes | 4.4 | 0 |
| barry-far-vless | 6042 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 5711 | yes | 3.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 0.72 | 0 |
| mahdibland-V2RayAggregator | 4332 | yes | 2.36 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 42 |
| geo | 39 |
| cn-block | 36 |
| speed | 11 |
