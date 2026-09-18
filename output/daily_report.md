# AutoNodes 每日报告

生成时间：2026-09-18 06:33:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83214 |
| 去重后节点数 | 22880 |
| TCP 可达数 | 3000 |
| 真测通过数 | 481 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22880 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 77.2 |
| geo | 1.6 |
| probe | 280.9 |
| real_test | 313.3 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 45 | 35 | 10 | 77.8% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 184 | 174 | 10 | 94.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 88 | 59 | 29 | 67.0% |
| vless | 355 | 192 | 163 | 54.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 70 |
| speed:TimeoutError | 36 |
| geo:ClientOSError | 30 |
| 204:ProxyError | 18 |
| speed:ClientOSError | 16 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 13 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5352 |
| ConnectionRefusedError | 826 |
| gaierror | 230 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.899 | prefer | 297 | 0.838 | 1561 |
| ermaozi | 0.765 | prefer | 46 | 0.761 | 378 |
| Surfboard-tg-mixed | 0.691 | observe | 209 | 0.612 | 7282 |
| DeltaKronecker-all | 0.586 | observe | 85 | 0.506 | 5931 |
| mheidari-all | 0.519 | observe | 55 | 0.436 | 15863 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| 10ium-ScrapeCategorize-Vless | 0.287 | observe | 2 | 0.5 | 5076 |
| Epodonios-all | 0.255 | observe | 0 | None | 7742 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8726 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.436 | 24 | 31 | 55 |
| 10ium-ScrapeCategorize-Vless | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.506 | 43 | 42 | 85 |
| Surfboard-tg-mixed | 0.612 | 128 | 81 | 209 |
| ermaozi | 0.761 | 35 | 11 | 46 |
| Au1rxx-base64 | 0.838 | 249 | 48 | 297 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15863 | yes | 3.21 | 0 |
| SoliSpirit-all | 8726 | yes | 2.62 | 0 |
| Epodonios-all | 7742 | yes | 3.6 | 0 |
| Surfboard-tg-mixed | 7282 | yes | 2.93 | 0 |
| barry-far-vless | 5988 | yes | 1.65 | 0 |
| DeltaKronecker-all | 5931 | yes | 3.73 | 0 |
| Surfboard-tg-vless | 5769 | yes | 2.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 1.0 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 1.45 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 100 |
| speed | 55 |
| 204 | 36 |
| cn-block | 25 |
