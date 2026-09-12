# AutoNodes 每日报告

生成时间：2026-09-12 18:28:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 83355 |
| 去重后节点数 | 22917 |
| TCP 可达数 | 3000 |
| 真测通过数 | 472 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22917 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 86.4 |
| geo | 1.4 |
| probe | 283.8 |
| real_test | 220.1 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 23 | 6 | 17 | 26.1% |
| hysteria2 | 27 | 26 | 1 | 96.3% |
| shadowsocks | 146 | 132 | 14 | 90.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 39 | 17 | 22 | 43.6% |
| vless | 409 | 290 | 119 | 70.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 52 |
| 204:TimeoutError | 37 |
| speed:ClientOSError | 21 |
| 204:ProxyError | 18 |
| cn-block:ClientOSError | 11 |
| cn-block:TimeoutError | 11 |
| speed:TimeoutError | 9 |
| 204:ProxyConnectionError | 4 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:47628: bind: address already in use | 1 |
| geo:ProxyError | 1 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5020 |
| ConnectionRefusedError | 889 |
| gaierror | 494 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | prefer | 47 | 0.872 | 15867 |
| Au1rxx-base64 | 0.922 | prefer | 315 | 0.86 | 1604 |
| DeltaKronecker-all | 0.682 | observe | 169 | 0.604 | 5970 |
| Surfboard-tg-mixed | 0.636 | observe | 88 | 0.557 | 7345 |
| ermaozi | 0.338 | observe | 19 | 0.316 | 393 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 177 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7800 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8543 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| ermaozi | 0.316 | 6 | 13 | 19 |
| Surfboard-tg-mixed | 0.557 | 49 | 39 | 88 |
| DeltaKronecker-all | 0.604 | 102 | 67 | 169 |
| Au1rxx-base64 | 0.86 | 271 | 44 | 315 |
| mheidari-all | 0.872 | 41 | 6 | 47 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15867 | yes | 5.1 | 0 |
| SoliSpirit-all | 8543 | yes | 3.94 | 0 |
| Epodonios-all | 7800 | yes | 2.12 | 0 |
| Surfboard-tg-mixed | 7345 | yes | 4.64 | 0 |
| barry-far-vless | 6127 | yes | 2.64 | 0 |
| DeltaKronecker-all | 5970 | yes | 5.25 | 0 |
| Surfboard-tg-vless | 5912 | yes | 3.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 2.93 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 1.53 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.72 | 0 |

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
| 204 | 61 |
| geo | 56 |
| speed | 32 |
| cn-block | 24 |
| sing-box exited 1 | 1 |
