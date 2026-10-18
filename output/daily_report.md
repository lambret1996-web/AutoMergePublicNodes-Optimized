# AutoNodes 每日报告

生成时间：2026-10-18 03:45:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99131 |
| 去重后节点数 | 27859 |
| TCP 可达数 | 3000 |
| 真测通过数 | 547 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27859 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 83.9 |
| geo | 1.8 |
| probe | 323.1 |
| real_test | 418.2 |
| tcp | 48.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 102 | 52 | 50 | 51.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 149 | 143 | 6 | 96.0% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 36 | 35 | 1 | 97.2% |
| vless | 508 | 293 | 215 | 57.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 105 |
| 204:ProxyError | 51 |
| geo:ClientOSError | 28 |
| speed:TimeoutError | 23 |
| speed:ClientOSError | 23 |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 15 |
| cn-block:ProxyError | 5 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7029 |
| ConnectionRefusedError | 1047 |
| gaierror | 262 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | prefer | 490 | 0.865 | 1798 |
| Surfboard-tg-mixed | 0.612 | observe | 75 | 0.533 | 7181 |
| ermaozi | 0.552 | observe | 103 | 0.524 | 710 |
| DeltaKronecker-all | 0.337 | observe | 13 | 0.308 | 4999 |
| mheidari-all | 0.266 | observe | 138 | 0.181 | 23946 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Epodonios-all | 0.255 | observe | 0 | None | 7667 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9901 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5616 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.181 | 25 | 113 | 138 |
| DeltaKronecker-all | 0.308 | 4 | 9 | 13 |
| ermaozi | 0.524 | 54 | 49 | 103 |
| Surfboard-tg-mixed | 0.533 | 40 | 35 | 75 |
| Au1rxx-base64 | 0.865 | 424 | 66 | 490 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23946 | yes | 4.6 | 0 |
| SoliSpirit-all | 9901 | yes | 3.7 | 0 |
| Epodonios-all | 7667 | yes | 4.85 | 0 |
| Surfboard-tg-mixed | 7181 | yes | 3.65 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.0 | 0 |
| barry-far-vless | 5884 | yes | 2.54 | 0 |
| Surfboard-tg-vless | 5616 | yes | 3.0 | 0 |
| DeltaKronecker-all | 4999 | yes | 5.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 2.4 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 1.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 134 |
| 204 | 66 |
| speed | 46 |
| cn-block | 28 |
