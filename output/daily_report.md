# AutoNodes 每日报告

生成时间：2026-10-19 03:55:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 97333 |
| 去重后节点数 | 27718 |
| TCP 可达数 | 3000 |
| 真测通过数 | 473 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27718 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 82.8 |
| geo | 1.5 |
| probe | 262.4 |
| real_test | 336.0 |
| tcp | 48.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 16 | 33 | 32.7% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 123 | 115 | 8 | 93.5% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 40 | 38 | 2 | 95.0% |
| vless | 451 | 279 | 172 | 61.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 75 |
| speed:ClientOSError | 26 |
| geo:ClientOSError | 25 |
| 204:ProxyError | 24 |
| cn-block:TimeoutError | 19 |
| 204:ProxyConnectionError | 16 |
| 204:TimeoutError | 11 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7004 |
| ConnectionRefusedError | 1061 |
| gaierror | 396 |
| OSError | 240 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.943 | prefer | 407 | 0.877 | 1698 |
| mheidari-all | 0.503 | observe | 213 | 0.423 | 23518 |
| Surfboard-tg-mixed | 0.446 | observe | 8 | 0.625 | 7003 |
| ermaozi | 0.374 | observe | 50 | 0.34 | 696 |
| DeltaKronecker-all | 0.361 | observe | 10 | 0.4 | 4750 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| Epodonios-all | 0.255 | observe | 0 | None | 7467 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9820 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5523 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.34 | 17 | 33 | 50 |
| DeltaKronecker-all | 0.4 | 4 | 6 | 10 |
| mheidari-all | 0.423 | 90 | 123 | 213 |
| Surfboard-tg-mixed | 0.625 | 5 | 3 | 8 |
| Au1rxx-base64 | 0.877 | 357 | 50 | 407 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23518 | yes | 7.04 | 0 |
| SoliSpirit-all | 9820 | yes | 2.39 | 0 |
| Epodonios-all | 7467 | yes | 6.38 | 0 |
| Surfboard-tg-mixed | 7003 | yes | 4.15 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.04 | 0 |
| barry-far-vless | 5700 | yes | 0.95 | 0 |
| Surfboard-tg-vless | 5523 | yes | 4.44 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 1.19 | 0 |
| DeltaKronecker-all | 4750 | yes | 3.71 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 3.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 101 |
| 204 | 54 |
| speed | 35 |
| cn-block | 27 |
