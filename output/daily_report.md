# AutoNodes 每日报告

生成时间：2026-09-20 00:40:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 89876 |
| 去重后节点数 | 25286 |
| TCP 可达数 | 3000 |
| 真测通过数 | 612 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25286 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 75.1 |
| geo | 1.5 |
| probe | 347.8 |
| real_test | 497.7 |
| tcp | 42.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 20 | 4 | 83.3% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 187 | 176 | 11 | 94.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 42 | 32 | 10 | 76.2% |
| vless | 812 | 370 | 442 | 45.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 172 |
| speed:TimeoutError | 110 |
| geo:ClientOSError | 83 |
| speed:ClientOSError | 30 |
| cn-block:ClientOSError | 29 |
| cn-block:TimeoutError | 16 |
| 204:ProxyError | 10 |
| 204:TimeoutError | 9 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 3 |
| 204:ClientOSError | 2 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5915 |
| ConnectionRefusedError | 898 |
| gaierror | 407 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.921 | prefer | 300 | 0.86 | 1577 |
| ermaozi | 0.885 | prefer | 22 | 0.909 | 250 |
| Surfboard-tg-mixed | 0.708 | prefer | 267 | 0.629 | 7112 |
| mheidari-all | 0.423 | observe | 429 | 0.343 | 18979 |
| DeltaKronecker-all | 0.385 | observe | 57 | 0.298 | 6421 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5174 |
| Epodonios-all | 0.255 | observe | 0 | None | 7571 |
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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.298 | 17 | 40 | 57 |
| mheidari-all | 0.343 | 147 | 282 | 429 |
| Surfboard-tg-mixed | 0.629 | 168 | 99 | 267 |
| Au1rxx-base64 | 0.86 | 258 | 42 | 300 |
| ermaozi | 0.909 | 20 | 2 | 22 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18979 | yes | 5.84 | 0 |
| SoliSpirit-all | 8803 | yes | 4.17 | 0 |
| Epodonios-all | 7571 | yes | 3.33 | 0 |
| Surfboard-tg-mixed | 7112 | yes | 4.44 | 0 |
| DeltaKronecker-all | 6421 | yes | 6.09 | 0 |
| barry-far-vless | 5853 | yes | 3.24 | 0 |
| Surfboard-tg-vless | 5640 | yes | 4.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 3.02 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 1.98 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 255 |
| speed | 143 |
| cn-block | 48 |
| 204 | 22 |
