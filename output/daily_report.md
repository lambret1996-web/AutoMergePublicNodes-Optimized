# AutoNodes 每日报告

生成时间：2026-10-11 04:55:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 97524 |
| 去重后节点数 | 27403 |
| TCP 可达数 | 3000 |
| 真测通过数 | 555 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27403 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 81.8 |
| geo | 1.4 |
| probe | 414.0 |
| real_test | 615.4 |
| tcp | 46.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 2 | 6 | 25.0% |
| http | 38 | 34 | 4 | 89.5% |
| hysteria2 | 27 | 26 | 1 | 96.3% |
| shadowsocks | 125 | 113 | 12 | 90.4% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 158 | 143 | 15 | 90.5% |
| vless | 518 | 232 | 286 | 44.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 159 |
| speed:TimeoutError | 56 |
| geo:ClientOSError | 40 |
| speed:ClientOSError | 28 |
| cn-block:TimeoutError | 16 |
| 204:ClientOSError | 9 |
| 204:ProxyError | 9 |
| 204:TimeoutError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6336 |
| ConnectionRefusedError | 1050 |
| gaierror | 418 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | prefer | 390 | 0.918 | 1799 |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.624 | observe | 11 | 0.818 | 7087 |
| ermaozi-get_subscribe | 0.611 | observe | 27 | 0.593 | 610 |
| mheidari-all | 0.429 | observe | 419 | 0.348 | 23694 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4347 |
| DeltaKronecker-all | 0.272 | observe | 7 | 0.286 | 5009 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7576 |

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
| DeltaKronecker-all | 0.286 | 2 | 5 | 7 |
| ninja-vless | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.348 | 146 | 273 | 419 |
| ermaozi-get_subscribe | 0.593 | 16 | 11 | 27 |
| Surfboard-tg-mixed | 0.818 | 9 | 2 | 11 |
| Au1rxx-base64 | 0.918 | 358 | 32 | 390 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23694 | yes | 3.35 | 0 |
| SoliSpirit-all | 9365 | yes | 1.92 | 0 |
| Epodonios-all | 7576 | yes | 2.99 | 0 |
| Surfboard-tg-mixed | 7087 | yes | 2.54 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.56 | 0 |
| barry-far-vless | 5790 | yes | 1.07 | 0 |
| Surfboard-tg-vless | 5545 | yes | 2.42 | 0 |
| DeltaKronecker-all | 5009 | yes | 3.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 4999 | yes | 0.9 | 0 |
| mahdibland-V2RayAggregator | 4347 | yes | 1.83 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 199 |
| speed | 85 |
| 204 | 22 |
| cn-block | 20 |
