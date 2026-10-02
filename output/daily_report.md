# AutoNodes 每日报告

生成时间：2026-10-02 04:46:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98599 |
| 去重后节点数 | 27531 |
| TCP 可达数 | 3000 |
| 真测通过数 | 444 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27531 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 80.8 |
| geo | 1.5 |
| probe | 251.9 |
| real_test | 336.1 |
| tcp | 47.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 5 | 1 | 83.3% |
| http | 24 | 22 | 2 | 91.7% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 182 | 165 | 17 | 90.7% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 41 | 32 | 9 | 78.0% |
| vless | 415 | 206 | 209 | 49.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 105 |
| speed:TimeoutError | 49 |
| geo:ClientOSError | 24 |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 12 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6473 |
| ConnectionRefusedError | 1051 |
| gaierror | 415 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | prefer | 260 | 0.9 | 1731 |
| ermaozi | 0.909 | prefer | 24 | 0.917 | 618 |
| Surfboard-tg-mixed | 0.818 | prefer | 170 | 0.741 | 7165 |
| mheidari-all | 0.34 | observe | 217 | 0.258 | 23308 |
| ermaozi-get_subscribe | 0.339 | observe | 4 | 0.75 | 475 |
| DeltaKronecker-all | 0.337 | observe | 7 | 0.429 | 5603 |
| Epodonios-all | 0.255 | observe | 0 | None | 7654 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9200 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5778 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.258 | 56 | 161 | 217 |
| DeltaKronecker-all | 0.429 | 3 | 4 | 7 |
| Surfboard-tg-mixed | 0.741 | 126 | 44 | 170 |
| ermaozi-get_subscribe | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.9 | 234 | 26 | 260 |
| ermaozi | 0.917 | 22 | 2 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23308 | yes | 6.82 | 0 |
| SoliSpirit-all | 9200 | yes | 2.47 | 0 |
| Epodonios-all | 7654 | yes | 3.32 | 0 |
| Surfboard-tg-mixed | 7165 | yes | 3.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.41 | 0 |
| barry-far-vless | 6015 | yes | 2.71 | 0 |
| Surfboard-tg-vless | 5778 | yes | 5.91 | 0 |
| DeltaKronecker-all | 5603 | yes | 4.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 1.9 | 0 |
| mahdibland-V2RayAggregator | 4310 | yes | 2.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 132 |
| speed | 58 |
| cn-block | 28 |
| 204 | 23 |
