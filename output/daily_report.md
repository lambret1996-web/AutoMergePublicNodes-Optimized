# AutoNodes 每日报告

生成时间：2026-09-19 12:29:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 88011 |
| 去重后节点数 | 25187 |
| TCP 可达数 | 3000 |
| 真测通过数 | 493 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25187 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 96.9 |
| geo | 1.4 |
| probe | 206.2 |
| real_test | 192.1 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 50 | 38 | 12 | 76.0% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 169 | 152 | 17 | 89.9% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 30 | 11 | 19 | 36.7% |
| vless | 416 | 271 | 145 | 65.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 47 |
| cn-block:ClientOSError | 34 |
| 204:TimeoutError | 22 |
| 204:ProxyError | 20 |
| geo:TimeoutError | 19 |
| speed:ClientOSError | 16 |
| speed:TimeoutError | 15 |
| cn-block:TimeoutError | 13 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6076 |
| ConnectionRefusedError | 891 |
| gaierror | 322 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | prefer | 327 | 0.884 | 1571 |
| ermaozi | 0.75 | prefer | 51 | 0.745 | 358 |
| Surfboard-tg-mixed | 0.671 | observe | 213 | 0.592 | 7474 |
| mheidari-all | 0.492 | observe | 83 | 0.41 | 19088 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| roosterkid-openproxylist-v2ray | 0.317 | observe | 2 | 1.0 | 150 |
| ermaozi-get_subscribe | 0.27 | observe | 1 | 1.0 | 387 |
| DeltaKronecker-all | 0.263 | observe | 8 | 0.25 | 6421 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5174 |
| Epodonios-all | 0.255 | observe | 0 | None | 7699 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.25 | 2 | 6 | 8 |
| mheidari-all | 0.41 | 34 | 49 | 83 |
| Surfboard-tg-mixed | 0.592 | 126 | 87 | 213 |
| ermaozi | 0.745 | 38 | 13 | 51 |
| Au1rxx-base64 | 0.884 | 289 | 38 | 327 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19088 | yes | 3.11 | 0 |
| SoliSpirit-all | 9271 | yes | 1.22 | 0 |
| Epodonios-all | 7699 | yes | 1.87 | 0 |
| Surfboard-tg-mixed | 7474 | yes | 2.28 | 0 |
| DeltaKronecker-all | 6421 | yes | 1.76 | 0 |
| Surfboard-tg-vless | 6006 | yes | 2.07 | 0 |
| barry-far-vless | 5996 | yes | 0.78 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 0.96 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 1.68 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.83 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 67 |
| cn-block | 50 |
| 204 | 48 |
| speed | 31 |
