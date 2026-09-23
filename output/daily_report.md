# AutoNodes 每日报告

生成时间：2026-09-23 06:35:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96782 |
| 去重后节点数 | 26365 |
| TCP 可达数 | 3000 |
| 真测通过数 | 470 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26365 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 77.6 |
| geo | 1.5 |
| probe | 279.3 |
| real_test | 335.5 |
| tcp | 42.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 66 | 46 | 20 | 69.7% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 176 | 169 | 7 | 96.0% |
| socks | 11 | 8 | 3 | 72.7% |
| trojan | 35 | 13 | 22 | 37.1% |
| vless | 533 | 214 | 319 | 40.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 88 |
| speed:ClientOSError | 71 |
| geo:ClientOSError | 47 |
| speed:TimeoutError | 47 |
| cn-block:ClientOSError | 36 |
| 204:TimeoutError | 30 |
| 204:ProxyError | 25 |
| cn-block:TimeoutError | 21 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6124 |
| ConnectionRefusedError | 935 |
| gaierror | 332 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | prefer | 301 | 0.804 | 1591 |
| ermaozi | 0.743 | prefer | 57 | 0.737 | 346 |
| Surfboard-tg-mixed | 0.549 | observe | 224 | 0.469 | 7168 |
| mheidari-all | 0.392 | observe | 235 | 0.311 | 22274 |
| DeltaKronecker-all | 0.332 | observe | 14 | 0.286 | 6324 |
| ermaozi-get_subscribe | 0.296 | observe | 10 | 0.4 | 372 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5131 |
| Epodonios-all | 0.255 | observe | 0 | None | 7633 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8897 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.286 | 4 | 10 | 14 |
| mheidari-all | 0.311 | 73 | 162 | 235 |
| ermaozi-get_subscribe | 0.4 | 4 | 6 | 10 |
| Surfboard-tg-mixed | 0.469 | 105 | 119 | 224 |
| ermaozi | 0.737 | 42 | 15 | 57 |
| Au1rxx-base64 | 0.804 | 242 | 59 | 301 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22274 | yes | 6.08 | 0 |
| SoliSpirit-all | 8897 | yes | 1.64 | 0 |
| Epodonios-all | 7633 | yes | 0.38 | 0 |
| Surfboard-tg-mixed | 7168 | yes | 4.37 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.27 | 0 |
| DeltaKronecker-all | 6324 | yes | 6.19 | 0 |
| barry-far-vless | 6054 | yes | 0.69 | 0 |
| Surfboard-tg-vless | 5836 | yes | 3.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 0.96 | 0 |
| mahdibland-V2RayAggregator | 4187 | yes | 0.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 136 |
| speed | 118 |
| 204 | 59 |
| cn-block | 59 |
