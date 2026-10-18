# AutoNodes 每日报告

生成时间：2026-10-18 15:42:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 98080 |
| 去重后节点数 | 27710 |
| TCP 可达数 | 3000 |
| 真测通过数 | 388 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27710 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 83.5 |
| geo | 1.5 |
| probe | 278.5 |
| real_test | 243.1 |
| tcp | 47.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 30 | 20 | 10 | 66.7% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 133 | 118 | 15 | 88.7% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 45 | 26 | 19 | 57.8% |
| vless | 290 | 210 | 80 | 72.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 43 |
| cn-block:TimeoutError | 20 |
| 204:ProxyError | 17 |
| geo:ClientOSError | 16 |
| speed:ClientOSError | 12 |
| geo:TimeoutError | 6 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 3 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6622 |
| ConnectionRefusedError | 1084 |
| gaierror | 475 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.908 | prefer | 339 | 0.841 | 1729 |
| mheidari-all | 0.898 | prefer | 31 | 0.839 | 23775 |
| ermaozi | 0.682 | observe | 30 | 0.667 | 639 |
| Surfboard-tg-mixed | 0.622 | observe | 94 | 0.543 | 7095 |
| DeltaKronecker-all | 0.356 | observe | 19 | 0.263 | 4750 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| Epodonios-all | 0.255 | observe | 0 | None | 7485 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10058 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.263 | 5 | 14 | 19 |
| Surfboard-tg-mixed | 0.543 | 51 | 43 | 94 |
| ermaozi | 0.667 | 20 | 10 | 30 |
| mheidari-all | 0.839 | 26 | 5 | 31 |
| Au1rxx-base64 | 0.841 | 285 | 54 | 339 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23775 | yes | 8.05 | 0 |
| SoliSpirit-all | 10058 | yes | 2.33 | 0 |
| Epodonios-all | 7485 | yes | 6.56 | 0 |
| Surfboard-tg-mixed | 7095 | yes | 4.19 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.94 | 0 |
| barry-far-vless | 5815 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 5602 | yes | 4.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 0.79 | 0 |
| DeltaKronecker-all | 4750 | yes | 5.83 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 1.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 62 |
| cn-block | 27 |
| geo | 22 |
| speed | 15 |
