# AutoNodes 每日报告

生成时间：2026-09-19 06:31:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84235 |
| 去重后节点数 | 23101 |
| TCP 可达数 | 3000 |
| 真测通过数 | 555 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23101 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 29.2 |
| geo | 1.4 |
| probe | 275.8 |
| real_test | 291.7 |
| tcp | 38.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 50 | 38 | 12 | 76.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 195 | 177 | 18 | 90.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 46 | 28 | 18 | 60.9% |
| vless | 486 | 292 | 194 | 60.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 83 |
| speed:TimeoutError | 28 |
| geo:ClientOSError | 26 |
| speed:ClientOSError | 24 |
| cn-block:TimeoutError | 24 |
| 204:ProxyError | 17 |
| 204:TimeoutError | 17 |
| cn-block:ClientOSError | 11 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5454 |
| ConnectionRefusedError | 801 |
| gaierror | 339 |
| OSError | 14 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | prefer | 327 | 0.869 | 1702 |
| ermaozi | 0.764 | prefer | 50 | 0.76 | 358 |
| roosterkid-openproxylist-v2ray | 0.727 | prefer | 13 | 1.0 | 150 |
| Surfboard-tg-mixed | 0.685 | observe | 241 | 0.606 | 7238 |
| mheidari-all | 0.625 | observe | 86 | 0.547 | 16187 |
| DeltaKronecker-all | 0.4 | observe | 73 | 0.315 | 6040 |
| Au1rxx-clash | 0.379 | observe | 2 | 1.0 | 1703 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4251 |
| ermaozi-get_subscribe | 0.27 | observe | 1 | 1.0 | 387 |
| Epodonios-all | 0.255 | observe | 0 | None | 7734 |

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
| MatinGhanbari-all-sub | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.315 | 23 | 50 | 73 |
| mheidari-all | 0.547 | 47 | 39 | 86 |
| Surfboard-tg-mixed | 0.606 | 146 | 95 | 241 |
| ermaozi | 0.76 | 38 | 12 | 50 |
| Au1rxx-base64 | 0.869 | 284 | 43 | 327 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16187 | yes | 3.2 | 0 |
| SoliSpirit-all | 8922 | yes | 2.45 | 0 |
| Epodonios-all | 7734 | yes | 2.13 | 0 |
| Surfboard-tg-mixed | 7238 | yes | 2.64 | 0 |
| barry-far-vless | 6042 | yes | 1.81 | 0 |
| DeltaKronecker-all | 6040 | yes | 3.33 | 0 |
| Surfboard-tg-vless | 5783 | yes | 3.65 | 0 |
| 10ium-ScrapeCategorize-Vless | 5174 | yes | 4.15 | 0 |
| mahdibland-V2RayAggregator | 4251 | yes | 2.35 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 112 |
| speed | 53 |
| 204 | 40 |
| cn-block | 39 |
