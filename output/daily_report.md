# AutoNodes 每日报告

生成时间：2026-10-07 18:46:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 98112 |
| 去重后节点数 | 27346 |
| TCP 可达数 | 3000 |
| 真测通过数 | 386 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27346 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.4 |
| generate | 90.9 |
| geo | 1.5 |
| probe | 304.1 |
| real_test | 172.2 |
| tcp | 46.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 10 | 1 | 9 | 10.0% |
| http | 28 | 16 | 12 | 57.1% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 143 | 127 | 16 | 88.8% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 88 | 75 | 13 | 85.2% |
| vless | 202 | 147 | 55 | 72.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 30 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 16 |
| speed:ClientOSError | 11 |
| speed:TimeoutError | 8 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 4 |
| geo:ClientOSError | 4 |
| 204:ProxyConnectionError | 3 |
| geo:ProxyError | 2 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6363 |
| ConnectionRefusedError | 1024 |
| gaierror | 395 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | prefer | 303 | 0.888 | 1823 |
| mheidari-all | 0.948 | prefer | 51 | 0.882 | 23074 |
| Surfboard-tg-mixed | 0.633 | observe | 83 | 0.554 | 7069 |
| ermaozi | 0.593 | observe | 28 | 0.571 | 664 |
| DeltaKronecker-all | 0.474 | observe | 15 | 0.467 | 5344 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7546 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.135 | 10 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.1 | 1 | 9 | 10 |
| DeltaKronecker-all | 0.467 | 7 | 8 | 15 |
| Surfboard-tg-mixed | 0.554 | 46 | 37 | 83 |
| ermaozi | 0.571 | 16 | 12 | 28 |
| mheidari-all | 0.882 | 45 | 6 | 51 |
| Au1rxx-base64 | 0.888 | 269 | 34 | 303 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23074 | yes | 6.69 | 0 |
| SoliSpirit-all | 9241 | yes | 4.18 | 0 |
| Epodonios-all | 7546 | yes | 6.99 | 0 |
| Surfboard-tg-mixed | 7069 | yes | 4.45 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.85 | 0 |
| barry-far-vless | 5859 | yes | 3.14 | 0 |
| Surfboard-tg-vless | 5616 | yes | 4.22 | 0 |
| DeltaKronecker-all | 5344 | yes | 6.22 | 0 |
| 10ium-ScrapeCategorize-Vless | 5138 | yes | 4.43 | 0 |
| mahdibland-V2RayAggregator | 4418 | yes | 3.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 53 |
| cn-block | 24 |
| speed | 19 |
| geo | 11 |
