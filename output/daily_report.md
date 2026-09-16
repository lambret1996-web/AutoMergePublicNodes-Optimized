# AutoNodes 每日报告

生成时间：2026-09-16 12:33:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 87305 |
| 去重后节点数 | 24333 |
| TCP 可达数 | 3000 |
| 真测通过数 | 474 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24333 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 135.1 |
| geo | 1.6 |
| probe | 276.8 |
| real_test | 229.7 |
| tcp | 41.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 70 | 46 | 24 | 65.7% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 151 | 140 | 11 | 92.7% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 38 | 36 | 2 | 94.7% |
| vless | 321 | 232 | 89 | 72.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 29 |
| geo:ClientOSError | 26 |
| cn-block:TimeoutError | 20 |
| cn-block:ClientOSError | 14 |
| speed:ClientOSError | 12 |
| 204:TimeoutError | 9 |
| geo:TimeoutError | 8 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:exit-country | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32123: bind: address already in use | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5727 |
| ConnectionRefusedError | 920 |
| gaierror | 429 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | prefer | 287 | 0.871 | 1684 |
| DeltaKronecker-all | 0.842 | prefer | 40 | 0.775 | 6081 |
| Surfboard-tg-mixed | 0.808 | prefer | 134 | 0.731 | 7446 |
| mheidari-all | 0.761 | prefer | 67 | 0.687 | 16003 |
| ermaozi | 0.713 | prefer | 54 | 0.704 | 407 |
| ermaozi-get_subscribe | 0.438 | observe | 18 | 0.444 | 438 |
| roosterkid-openproxylist-v2ray | 0.275 | observe | 3 | 0.667 | 150 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5115 |
| Epodonios-all | 0.255 | observe | 0 | None | 7906 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.444 | 8 | 10 | 18 |
| roosterkid-openproxylist-v2ray | 0.667 | 2 | 1 | 3 |
| mheidari-all | 0.687 | 46 | 21 | 67 |
| ermaozi | 0.704 | 38 | 16 | 54 |
| Surfboard-tg-mixed | 0.731 | 98 | 36 | 134 |
| DeltaKronecker-all | 0.775 | 31 | 9 | 40 |
| Au1rxx-base64 | 0.871 | 250 | 37 | 287 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16003 | yes | 4.46 | 0 |
| SoliSpirit-all | 8759 | yes | 2.54 | 0 |
| Epodonios-all | 7906 | yes | 5.13 | 0 |
| Surfboard-tg-mixed | 7446 | yes | 3.34 | 0 |
| barry-far-vless | 6260 | yes | 1.03 | 0 |
| DeltaKronecker-all | 6081 | yes | 5.27 | 0 |
| Surfboard-tg-vless | 6044 | yes | 3.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 4206 | yes | 0.14 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.13 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| cn-block | 37 |
| geo | 35 |
| speed | 17 |
| sing-box exited 1 | 1 |
