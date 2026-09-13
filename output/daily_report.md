# AutoNodes 每日报告

生成时间：2026-09-13 06:39:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94410 |
| 去重后节点数 | 25154 |
| TCP 可达数 | 3000 |
| 真测通过数 | 561 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25154 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 89.9 |
| geo | 1.6 |
| probe | 336.5 |
| real_test | 380.5 |
| tcp | 41.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 38 | 23 | 15 | 60.5% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 166 | 156 | 10 | 94.0% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 52 | 41 | 11 | 78.8% |
| vless | 532 | 312 | 220 | 58.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 78 |
| geo:ClientOSError | 47 |
| speed:ClientOSError | 40 |
| 204:ProxyError | 21 |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 20 |
| speed:TimeoutError | 18 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:exit-country | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5607 |
| ConnectionRefusedError | 972 |
| gaierror | 504 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.907 | prefer | 355 | 0.839 | 1728 |
| mheidari-all | 0.782 | prefer | 92 | 0.707 | 20709 |
| Surfboard-tg-mixed | 0.727 | prefer | 171 | 0.649 | 7432 |
| ermaozi | 0.684 | observe | 28 | 0.679 | 436 |
| DeltaKronecker-all | 0.467 | observe | 161 | 0.385 | 5970 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5301 |
| ermaozi-get_subscribe | 0.3 | observe | 10 | 0.4 | 464 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 83 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| Epodonios-all | 0.255 | observe | 0 | None | 7895 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.385 | 62 | 99 | 161 |
| ermaozi-get_subscribe | 0.4 | 4 | 6 | 10 |
| Surfboard-tg-mixed | 0.649 | 111 | 60 | 171 |
| ermaozi | 0.679 | 19 | 9 | 28 |
| mheidari-all | 0.707 | 65 | 27 | 92 |
| Au1rxx-base64 | 0.839 | 298 | 57 | 355 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20709 | yes | 6.42 | 0 |
| SoliSpirit-all | 8741 | yes | 5.11 | 0 |
| Epodonios-all | 7895 | yes | 3.63 | 0 |
| Surfboard-tg-mixed | 7432 | yes | 4.54 | 0 |
| barry-far-vless | 6247 | yes | 2.4 | 0 |
| Surfboard-tg-vless | 6027 | yes | 4.76 | 0 |
| DeltaKronecker-all | 5970 | yes | 6.12 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 3.63 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 3.35 | 0 |
| mahdibland-V2RayAggregator | 4221 | yes | 3.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 126 |
| speed | 59 |
| 204 | 44 |
| cn-block | 30 |
