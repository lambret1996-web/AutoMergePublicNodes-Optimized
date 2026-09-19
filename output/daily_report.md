# AutoNodes 每日报告

生成时间：2026-09-19 18:27:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87959 |
| 去重后节点数 | 25367 |
| TCP 可达数 | 3000 |
| 真测通过数 | 494 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25367 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 76.3 |
| geo | 1.4 |
| probe | 228.8 |
| real_test | 176.8 |
| tcp | 41.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 23 | 4 | 85.2% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 154 | 139 | 15 | 90.3% |
| trojan | 10 | 6 | 4 | 60.0% |
| vless | 449 | 308 | 141 | 68.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 41 |
| cn-block:ClientOSError | 33 |
| 204:TimeoutError | 26 |
| speed:ClientOSError | 16 |
| cn-block:TimeoutError | 11 |
| geo:TimeoutError | 11 |
| 204:ProxyError | 10 |
| speed:TimeoutError | 9 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5539 |
| ConnectionRefusedError | 912 |
| gaierror | 469 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | prefer | 298 | 0.869 | 1650 |
| ermaozi | 0.862 | prefer | 25 | 0.88 | 250 |
| Surfboard-tg-mixed | 0.762 | prefer | 177 | 0.684 | 7303 |
| mheidari-all | 0.65 | observe | 147 | 0.571 | 19206 |
| DeltaKronecker-all | 0.557 | observe | 6 | 1.0 | 6421 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9224 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5863 |
| barry-far-vless | 0.255 | observe | 0 | None | 6115 |

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
| Epodonios-all | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.571 | 84 | 63 | 147 |
| Surfboard-tg-mixed | 0.684 | 121 | 56 | 177 |
| Au1rxx-base64 | 0.869 | 259 | 39 | 298 |
| ermaozi | 0.88 | 22 | 3 | 25 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 6 | 0 | 6 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19206 | yes | 3.65 | 0 |
| SoliSpirit-all | 9224 | yes | 1.76 | 0 |
| Epodonios-all | 7753 | yes | 2.3 | 0 |
| Surfboard-tg-mixed | 7303 | yes | 3.23 | 0 |
| DeltaKronecker-all | 6421 | yes | 4.0 | 0 |
| barry-far-vless | 6115 | yes | 0.93 | 0 |
| Surfboard-tg-vless | 5863 | yes | 2.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 0.58 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 1.23 | 0 |
| MatinGhanbari-all-sub | 3995 | yes | 0.42 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 52 |
| cn-block | 48 |
| 204 | 40 |
| speed | 25 |
