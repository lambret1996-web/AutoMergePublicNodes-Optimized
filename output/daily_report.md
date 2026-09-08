# AutoNodes 每日报告

生成时间：2026-09-08 00:33:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 91664 |
| 去重后节点数 | 25195 |
| TCP 可达数 | 3000 |
| 真测通过数 | 736 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25195 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 35.0 |
| geo | 1.5 |
| probe | 86.3 |
| real_test | 158.7 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 6 | 1 | 85.7% |
| http | 56 | 55 | 1 | 98.2% |
| hysteria2 | 28 | 27 | 1 | 96.4% |
| shadowsocks | 191 | 182 | 9 | 95.3% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 54 | 38 | 16 | 70.4% |
| vless | 624 | 424 | 200 | 67.9% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 59 |
| speed:TimeoutError | 43 |
| geo:ClientOSError | 39 |
| cn-block:ClientOSError | 24 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 17 |
| 204:ProxyError | 11 |
| 204:TimeoutError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:44716: bind: address already in use | 1 |
| 204:ServerDisconnectedError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5968 |
| ConnectionRefusedError | 987 |
| gaierror | 320 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 377 | 0.931 | 1805 |
| ermaozi | 0.993 | prefer | 38 | 1.0 | 450 |
| ermaozi-get_subscribe | 0.86 | prefer | 18 | 0.944 | 465 |
| Surfboard-tg-mixed | 0.833 | prefer | 245 | 0.755 | 7423 |
| mheidari-all | 0.626 | observe | 181 | 0.547 | 16494 |
| xiaoji235-airport-v2ray-all | 0.513 | observe | 28 | 0.429 | 5750 |
| DeltaKronecker-all | 0.483 | observe | 65 | 0.4 | 6417 |
| tg-oneclickvpnkeys | 0.457 | observe | 7 | 0.857 | 196 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.4 | 26 | 39 | 65 |
| xiaoji235-airport-v2ray-all | 0.429 | 12 | 16 | 28 |
| mheidari-all | 0.547 | 99 | 82 | 181 |
| Surfboard-tg-mixed | 0.755 | 185 | 60 | 245 |
| tg-oneclickvpnkeys | 0.857 | 6 | 1 | 7 |
| Au1rxx-base64 | 0.931 | 351 | 26 | 377 |
| ermaozi-get_subscribe | 0.944 | 17 | 1 | 18 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16494 | yes | 5.85 | 0 |
| SoliSpirit-all | 8733 | yes | 3.56 | 0 |
| Epodonios-all | 7917 | yes | 4.17 | 0 |
| Surfboard-tg-mixed | 7423 | yes | 4.44 | 0 |
| barry-far-vless | 6444 | yes | 3.16 | 0 |
| DeltaKronecker-all | 6417 | yes | 5.73 | 0 |
| Surfboard-tg-vless | 6226 | yes | 3.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 2.87 | 0 |
| mahdibland-V2RayAggregator | 4218 | yes | 0.51 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.25 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 100 |
| speed | 64 |
| cn-block | 44 |
| 204 | 21 |
| sing-box exited 1 | 1 |
