# AutoNodes 每日报告

生成时间：2026-09-13 00:44:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 94116 |
| 去重后节点数 | 25341 |
| TCP 可达数 | 3000 |
| 真测通过数 | 670 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25341 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 84.6 |
| geo | 1.4 |
| probe | 389.5 |
| real_test | 656.7 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 23 | 6 | 17 | 26.1% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 187 | 178 | 9 | 95.2% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 28 | 12 | 16 | 42.9% |
| vless | 1084 | 448 | 636 | 41.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 228 |
| geo:ClientOSError | 128 |
| speed:TimeoutError | 110 |
| speed:ClientOSError | 97 |
| cn-block:ClientOSError | 65 |
| 204:ProxyError | 17 |
| 204:TimeoutError | 14 |
| cn-block:TimeoutError | 11 |
| 204:ProxyConnectionError | 6 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5809 |
| ConnectionRefusedError | 966 |
| gaierror | 468 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | prefer | 361 | 0.911 | 1631 |
| Surfboard-tg-mixed | 0.915 | prefer | 83 | 0.843 | 7440 |
| DeltaKronecker-all | 0.43 | observe | 264 | 0.348 | 5970 |
| mheidari-all | 0.358 | observe | 614 | 0.277 | 20520 |
| ermaozi | 0.338 | observe | 19 | 0.316 | 393 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 141 |
| Epodonios-all | 0.255 | observe | 0 | None | 7839 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8833 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.163 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.277 | 170 | 444 | 614 |
| ermaozi | 0.316 | 6 | 13 | 19 |
| DeltaKronecker-all | 0.348 | 92 | 172 | 264 |
| Surfboard-tg-mixed | 0.843 | 70 | 13 | 83 |
| Au1rxx-base64 | 0.911 | 329 | 32 | 361 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20520 | yes | 6.33 | 0 |
| SoliSpirit-all | 8833 | yes | 2.44 | 0 |
| Epodonios-all | 7839 | yes | 4.92 | 0 |
| Surfboard-tg-mixed | 7440 | yes | 3.59 | 0 |
| barry-far-vless | 6210 | yes | 0.98 | 0 |
| Surfboard-tg-vless | 6133 | yes | 3.8 | 0 |
| DeltaKronecker-all | 5970 | yes | 4.32 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 1.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 2.12 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 3.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 356 |
| speed | 207 |
| cn-block | 78 |
| 204 | 40 |
