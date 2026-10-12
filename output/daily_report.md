# AutoNodes 每日报告

生成时间：2026-10-12 21:16:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 100399 |
| 去重后节点数 | 27904 |
| TCP 可达数 | 3000 |
| 真测通过数 | 497 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27904 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 87.9 |
| geo | 1.7 |
| probe | 373.4 |
| real_test | 365.1 |
| tcp | 48.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 47 | 24 | 23 | 51.1% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 140 | 129 | 11 | 92.1% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 174 | 153 | 21 | 87.9% |
| vless | 243 | 167 | 76 | 68.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 34 |
| 204:ProxyError | 26 |
| 204:TimeoutError | 25 |
| geo:ClientOSError | 13 |
| cn-block:ClientOSError | 10 |
| cn-block:ProxyError | 7 |
| geo:TimeoutError | 7 |
| speed:TimeoutError | 6 |
| speed:ClientOSError | 4 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6668 |
| ConnectionRefusedError | 1042 |
| gaierror | 293 |
| OSError | 241 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | prefer | 356 | 0.91 | 1842 |
| mheidari-all | 0.92 | prefer | 48 | 0.854 | 23860 |
| Surfboard-tg-mixed | 0.759 | prefer | 51 | 0.686 | 7235 |
| DeltaKronecker-all | 0.637 | observe | 120 | 0.558 | 5701 |
| ermaozi | 0.578 | observe | 47 | 0.553 | 675 |
| ermaozi-get_subscribe | 0.333 | observe | 2 | 1.0 | 532 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5028 |
| Epodonios-all | 0.255 | observe | 0 | None | 7736 |

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
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.553 | 26 | 21 | 47 |
| DeltaKronecker-all | 0.558 | 67 | 53 | 120 |
| Surfboard-tg-mixed | 0.686 | 35 | 16 | 51 |
| mheidari-all | 0.854 | 41 | 7 | 48 |
| Au1rxx-base64 | 0.91 | 324 | 32 | 356 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23860 | yes | 5.75 | 0 |
| SoliSpirit-all | 9955 | yes | 3.11 | 0 |
| Epodonios-all | 7736 | yes | 6.64 | 0 |
| Surfboard-tg-mixed | 7235 | yes | 3.41 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.07 | 0 |
| barry-far-vless | 6023 | yes | 1.1 | 0 |
| Surfboard-tg-vless | 5776 | yes | 3.59 | 0 |
| DeltaKronecker-all | 5701 | yes | 6.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 5028 | yes | 4.09 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 2.88 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 51 |
| cn-block | 51 |
| geo | 21 |
| speed | 10 |
