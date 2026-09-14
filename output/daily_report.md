# AutoNodes 每日报告

生成时间：2026-09-14 00:36:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 89696 |
| 去重后节点数 | 25345 |
| TCP 可达数 | 3000 |
| 真测通过数 | 520 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25345 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 74.4 |
| geo | 1.4 |
| probe | 244.6 |
| real_test | 310.7 |
| tcp | 42.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 39 | 22 | 17 | 56.4% |
| hysteria2 | 26 | 24 | 2 | 92.3% |
| shadowsocks | 173 | 167 | 6 | 96.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 37 | 27 | 10 | 73.0% |
| vless | 501 | 276 | 225 | 55.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 61 |
| speed:TimeoutError | 50 |
| geo:ClientOSError | 40 |
| speed:ClientOSError | 32 |
| cn-block:ClientOSError | 26 |
| 204:ProxyError | 22 |
| cn-block:TimeoutError | 13 |
| 204:TimeoutError | 10 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5439 |
| ConnectionRefusedError | 987 |
| gaierror | 591 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.962 | prefer | 324 | 0.898 | 1660 |
| Surfboard-tg-mixed | 0.755 | prefer | 198 | 0.677 | 7507 |
| ermaozi | 0.637 | observe | 35 | 0.629 | 382 |
| mheidari-all | 0.457 | observe | 112 | 0.375 | 15930 |
| DeltaKronecker-all | 0.382 | observe | 61 | 0.295 | 5892 |
| xiaoji235-airport-v2ray-all | 0.366 | observe | 40 | 0.275 | 5301 |
| Epodonios-all | 0.255 | observe | 0 | None | 7970 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8791 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6135 |

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
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| 10ium-ScrapeCategorize-Vless | 0.25 | 1 | 3 | 4 |
| xiaoji235-airport-v2ray-all | 0.275 | 11 | 29 | 40 |
| DeltaKronecker-all | 0.295 | 18 | 43 | 61 |
| mheidari-all | 0.375 | 42 | 70 | 112 |
| ermaozi | 0.629 | 22 | 13 | 35 |
| Surfboard-tg-mixed | 0.677 | 134 | 64 | 198 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15930 | yes | 5.56 | 0 |
| SoliSpirit-all | 8791 | yes | 4.41 | 0 |
| Epodonios-all | 7970 | yes | 3.49 | 0 |
| Surfboard-tg-mixed | 7507 | yes | 4.24 | 0 |
| barry-far-vless | 6350 | yes | 3.68 | 0 |
| Surfboard-tg-vless | 6135 | yes | 4.77 | 0 |
| DeltaKronecker-all | 5892 | yes | 6.48 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 3.0 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 3.16 | 0 |
| mahdibland-V2RayAggregator | 4222 | yes | 0.85 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 102 |
| speed | 84 |
| cn-block | 40 |
| 204 | 36 |
