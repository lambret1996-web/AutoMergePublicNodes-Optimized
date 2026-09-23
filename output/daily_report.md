# AutoNodes 每日报告

生成时间：2026-09-23 00:39:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 88330 |
| 去重后节点数 | 25503 |
| TCP 可达数 | 3000 |
| 真测通过数 | 564 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25503 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 27.1 |
| geo | 1.4 |
| probe | 354.4 |
| real_test | 585.6 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 34 | 23 | 11 | 67.6% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 124 | 118 | 6 | 95.2% |
| socks | 13 | 10 | 3 | 76.9% |
| trojan | 74 | 40 | 34 | 54.1% |
| vless | 877 | 348 | 529 | 39.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 282 |
| speed:ClientOSError | 112 |
| geo:ClientOSError | 84 |
| speed:TimeoutError | 49 |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 13 |
| cn-block:ClientOSError | 11 |
| 204:TimeoutError | 9 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:38638: bind: address already in use | 1 |
| 204:ProxyConnectionError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6137 |
| ConnectionRefusedError | 932 |
| gaierror | 240 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.854 | prefer | 296 | 0.787 | 1717 |
| ermaozi | 0.755 | prefer | 29 | 0.759 | 325 |
| Surfboard-tg-mixed | 0.674 | observe | 30 | 0.6 | 7168 |
| mheidari-all | 0.538 | observe | 142 | 0.458 | 16262 |
| xiaoji235-airport-v2ray-all | 0.515 | observe | 16 | 0.5 | 4242 |
| DeltaKronecker-all | 0.424 | observe | 615 | 0.343 | 6324 |
| 10ium-ScrapeCategorize-Vless | 0.305 | observe | 10 | 0.3 | 4915 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| Epodonios-all | 0.255 | observe | 0 | None | 7638 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| 10ium-ScrapeCategorize-Vless | 0.3 | 3 | 7 | 10 |
| DeltaKronecker-all | 0.343 | 211 | 404 | 615 |
| mheidari-all | 0.458 | 65 | 77 | 142 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| xiaoji235-airport-v2ray-all | 0.5 | 8 | 8 | 16 |
| Surfboard-tg-mixed | 0.6 | 18 | 12 | 30 |
| ermaozi | 0.759 | 22 | 7 | 29 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16262 | yes | 5.25 | 0 |
| SoliSpirit-all | 8904 | yes | 3.58 | 0 |
| Epodonios-all | 7638 | yes | 3.37 | 0 |
| Surfboard-tg-mixed | 7168 | yes | 4.43 | 0 |
| DeltaKronecker-all | 6324 | yes | 4.63 | 0 |
| barry-far-vless | 6057 | yes | 0.91 | 0 |
| Surfboard-tg-vless | 5836 | yes | 4.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 1.49 | 0 |
| mahdibland-V2RayAggregator | 4252 | yes | 0.44 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 3.3 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 366 |
| speed | 162 |
| cn-block | 30 |
| 204 | 25 |
| sing-box exited 1 | 1 |
