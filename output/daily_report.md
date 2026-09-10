# AutoNodes 每日报告

生成时间：2026-09-10 00:34:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83955 |
| 去重后节点数 | 21995 |
| TCP 可达数 | 3000 |
| 真测通过数 | 504 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21995 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 75.4 |
| geo | 1.4 |
| probe | 235.5 |
| real_test | 306.8 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 26 | 19 | 7 | 73.1% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 189 | 179 | 10 | 94.7% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 38 | 33 | 5 | 86.8% |
| vless | 356 | 255 | 101 | 71.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 28 |
| speed:TimeoutError | 22 |
| geo:ClientOSError | 20 |
| cn-block:TimeoutError | 13 |
| speed:ClientOSError | 12 |
| cn-block:ClientOSError | 9 |
| 204:TimeoutError | 8 |
| 204:ProxyError | 5 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4734 |
| ConnectionRefusedError | 851 |
| gaierror | 337 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | prefer | 284 | 0.93 | 1529 |
| Surfboard-tg-mixed | 0.872 | prefer | 200 | 0.795 | 7448 |
| ermaozi | 0.731 | prefer | 26 | 0.731 | 410 |
| mheidari-all | 0.695 | observe | 63 | 0.619 | 16401 |
| DeltaKronecker-all | 0.535 | observe | 42 | 0.452 | 5187 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 147 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7910 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-ScrapeCategorize-Vless | 0.144 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 7 | 7 |
| DeltaKronecker-all | 0.452 | 19 | 23 | 42 |
| mheidari-all | 0.619 | 39 | 24 | 63 |
| ermaozi | 0.731 | 19 | 7 | 26 |
| Surfboard-tg-mixed | 0.795 | 159 | 41 | 200 |
| Au1rxx-base64 | 0.93 | 264 | 20 | 284 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16401 | yes | 5.01 | 0 |
| SoliSpirit-all | 8855 | yes | 2.84 | 0 |
| Epodonios-all | 7910 | yes | 2.78 | 0 |
| Surfboard-tg-mixed | 7448 | yes | 4.33 | 0 |
| barry-far-vless | 6329 | yes | 2.05 | 0 |
| Surfboard-tg-vless | 6108 | yes | 3.99 | 0 |
| DeltaKronecker-all | 5187 | yes | 5.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 1.23 | 0 |
| mahdibland-V2RayAggregator | 4247 | yes | 3.33 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 50 |
| speed | 34 |
| cn-block | 23 |
| 204 | 19 |
