# AutoNodes 每日报告

生成时间：2026-10-20 04:02:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 94707 |
| 去重后节点数 | 26190 |
| TCP 可达数 | 3000 |
| 真测通过数 | 339 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26190 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 82.6 |
| geo | 1.5 |
| probe | 210.6 |
| real_test | 226.1 |
| tcp | 44.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 24 | 20 | 54.5% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 119 | 111 | 8 | 93.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 32 | 28 | 4 | 87.5% |
| vless | 266 | 156 | 110 | 58.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 33 |
| 204:ProxyError | 27 |
| speed:TimeoutError | 17 |
| speed:ClientOSError | 15 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 14 |
| geo:ClientOSError | 13 |
| cn-block:ClientOSError | 5 |
| 204:ProxyConnectionError | 4 |
| speed:ClientPayloadError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6270 |
| ConnectionRefusedError | 1053 |
| gaierror | 309 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.877 | prefer | 309 | 0.822 | 1424 |
| zhangkai | 0.705 | prefer | 14 | 0.929 | 27 |
| mheidari-all | 0.552 | observe | 106 | 0.472 | 23317 |
| DeltaKronecker-all | 0.432 | observe | 14 | 0.429 | 3294 |
| ermaozi-get_subscribe | 0.395 | observe | 30 | 0.367 | 510 |
| Surfboard-tg-mixed | 0.372 | observe | 9 | 0.444 | 6911 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| Epodonios-all | 0.255 | observe | 0 | None | 7516 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| ermaozi-get_subscribe | 0.367 | 11 | 19 | 30 |
| DeltaKronecker-all | 0.429 | 6 | 8 | 14 |
| Surfboard-tg-mixed | 0.444 | 4 | 5 | 9 |
| mheidari-all | 0.472 | 50 | 56 | 106 |
| Au1rxx-base64 | 0.822 | 254 | 55 | 309 |
| zhangkai | 0.929 | 13 | 1 | 14 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23317 | yes | 5.71 | 0 |
| SoliSpirit-all | 10161 | yes | 3.66 | 0 |
| Epodonios-all | 7516 | yes | 6.01 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 4.38 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.26 | 0 |
| barry-far-vless | 5797 | yes | 0.8 | 0 |
| Surfboard-tg-vless | 5515 | yes | 3.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 1.35 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 1.12 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.88 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 46 |
| geo | 46 |
| speed | 33 |
| cn-block | 19 |
