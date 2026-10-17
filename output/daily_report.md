# AutoNodes 每日报告

生成时间：2026-10-17 15:22:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 99135 |
| 去重后节点数 | 27579 |
| TCP 可达数 | 3000 |
| 真测通过数 | 404 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27579 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 87.1 |
| geo | 1.5 |
| probe | 338.4 |
| real_test | 292.6 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 20 | 11 | 9 | 55.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 148 | 116 | 32 | 78.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 68 | 32 | 36 | 47.1% |
| vless | 325 | 228 | 97 | 70.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 69 |
| 204:ProxyError | 18 |
| speed:ClientOSError | 16 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 14 |
| 204:ProxyConnectionError | 11 |
| 204:ClientOSError | 10 |
| speed:TimeoutError | 8 |
| geo:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6716 |
| ConnectionRefusedError | 1037 |
| gaierror | 281 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.864 | prefer | 471 | 0.786 | 1993 |
| ermaozi | 0.57 | observe | 20 | 0.55 | 623 |
| Surfboard-tg-mixed | 0.398 | observe | 42 | 0.31 | 7171 |
| mheidari-all | 0.37 | observe | 16 | 0.312 | 23770 |
| ermaozi-get_subscribe | 0.275 | observe | 1 | 1.0 | 510 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1993 |
| Epodonios-all | 0.255 | observe | 0 | None | 7678 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9904 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.236 | 30 | 0.133 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.133 | 4 | 26 | 30 |
| Surfboard-tg-mixed | 0.31 | 13 | 29 | 42 |
| mheidari-all | 0.312 | 5 | 11 | 16 |
| ermaozi | 0.55 | 11 | 9 | 20 |
| Au1rxx-base64 | 0.786 | 370 | 101 | 471 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23770 | yes | 8.35 | 0 |
| SoliSpirit-all | 9904 | yes | 4.79 | 0 |
| Epodonios-all | 7678 | yes | 7.0 | 0 |
| Surfboard-tg-mixed | 7171 | yes | 4.58 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 4.24 | 0 |
| barry-far-vless | 5865 | yes | 4.45 | 0 |
| Surfboard-tg-vless | 5617 | yes | 4.78 | 0 |
| DeltaKronecker-all | 4999 | yes | 6.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 3.44 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 0.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 108 |
| speed | 24 |
| cn-block | 23 |
| geo | 22 |
