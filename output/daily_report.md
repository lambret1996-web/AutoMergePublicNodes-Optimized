# AutoNodes 每日报告

生成时间：2026-09-26 16:22:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96925 |
| 去重后节点数 | 26334 |
| TCP 可达数 | 3000 |
| 真测通过数 | 379 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26334 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 81.7 |
| geo | 1.4 |
| probe | 205.4 |
| real_test | 163.8 |
| tcp | 42.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 20 | 9 | 11 | 45.0% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 151 | 134 | 17 | 88.7% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 14 | 12 | 2 | 85.7% |
| vless | 260 | 204 | 56 | 78.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 39 |
| 204:ProxyError | 15 |
| cn-block:ClientOSError | 10 |
| cn-block:TimeoutError | 9 |
| speed:TimeoutError | 7 |
| geo:TimeoutError | 3 |
| speed:ClientOSError | 2 |
| geo:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5832 |
| ConnectionRefusedError | 959 |
| gaierror | 364 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.962 | prefer | 268 | 0.899 | 1642 |
| Surfboard-tg-mixed | 0.816 | prefer | 108 | 0.741 | 7263 |
| mheidari-all | 0.781 | prefer | 65 | 0.708 | 22551 |
| ermaozi | 0.433 | observe | 18 | 0.444 | 296 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7742 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| ermaozi | 0.444 | 8 | 10 | 18 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.708 | 46 | 19 | 65 |
| Surfboard-tg-mixed | 0.741 | 80 | 28 | 108 |
| Au1rxx-base64 | 0.899 | 241 | 27 | 268 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22551 | yes | 3.99 | 0 |
| SoliSpirit-all | 9122 | yes | 2.44 | 0 |
| Epodonios-all | 7742 | yes | 2.0 | 0 |
| Surfboard-tg-mixed | 7263 | yes | 2.6 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.3 | 0 |
| barry-far-vless | 6056 | yes | 0.69 | 0 |
| Surfboard-tg-vless | 5823 | yes | 2.26 | 0 |
| DeltaKronecker-all | 5512 | yes | 3.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 0.43 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 1.81 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 54 |
| cn-block | 20 |
| speed | 9 |
| geo | 5 |
