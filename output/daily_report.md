# AutoNodes 每日报告

生成时间：2026-10-09 05:22:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98041 |
| 去重后节点数 | 27746 |
| TCP 可达数 | 3000 |
| 真测通过数 | 534 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27746 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 89.9 |
| geo | 1.5 |
| probe | 393.7 |
| real_test | 572.3 |
| tcp | 46.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 2 | 3 | 40.0% |
| http | 66 | 50 | 16 | 75.8% |
| hysteria2 | 25 | 25 | 0 | 100.0% |
| shadowsocks | 160 | 145 | 15 | 90.6% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 99 | 88 | 11 | 88.9% |
| vless | 546 | 221 | 325 | 40.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 177 |
| speed:TimeoutError | 69 |
| geo:ClientOSError | 36 |
| speed:ClientOSError | 26 |
| 204:ProxyError | 23 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 11 |
| cn-block:ClientOSError | 9 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6123 |
| ConnectionRefusedError | 1019 |
| gaierror | 493 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | prefer | 363 | 0.906 | 1761 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.727 | prefer | 32 | 0.656 | 7069 |
| ermaozi-get_subscribe | 0.62 | observe | 50 | 0.6 | 607 |
| DeltaKronecker-all | 0.563 | observe | 16 | 0.562 | 5197 |
| mheidari-all | 0.369 | observe | 417 | 0.288 | 23125 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5081 |
| Epodonios-all | 0.255 | observe | 0 | None | 7569 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| SoliSpirit-all | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.288 | 120 | 297 | 417 |
| ninja-vless | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.562 | 9 | 7 | 16 |
| ermaozi-get_subscribe | 0.6 | 30 | 20 | 50 |
| Surfboard-tg-mixed | 0.656 | 21 | 11 | 32 |
| Au1rxx-base64 | 0.906 | 329 | 34 | 363 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23125 | yes | 4.71 | 0 |
| SoliSpirit-all | 9901 | yes | 1.77 | 0 |
| Epodonios-all | 7569 | yes | 2.85 | 0 |
| Surfboard-tg-mixed | 7069 | yes | 3.15 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.4 | 0 |
| barry-far-vless | 5823 | yes | 0.93 | 0 |
| Surfboard-tg-vless | 5581 | yes | 2.99 | 0 |
| DeltaKronecker-all | 5197 | yes | 4.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 5081 | yes | 0.74 | 0 |
| mahdibland-V2RayAggregator | 4362 | yes | 0.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 213 |
| speed | 95 |
| 204 | 35 |
| cn-block | 31 |
