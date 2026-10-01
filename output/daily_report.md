# AutoNodes 每日报告

生成时间：2026-10-01 11:52:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 98651 |
| 去重后节点数 | 27372 |
| TCP 可达数 | 3000 |
| 真测通过数 | 430 |
| verified 输出数 | 30 |
| global 输出数 | 30 |
| all 输出数 | 27372 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| generate | 80.5 |
| geo | 1.5 |
| probe | 282.2 |
| real_test | 172.1 |
| tcp | 45.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 166 | 143 | 23 | 86.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 49 | 43 | 6 | 87.8% |
| vless | 291 | 200 | 91 | 68.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 50 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 10 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 9 |
| geo:TimeoutError | 9 |
| 204:ClientOSError | 3 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6270 |
| ConnectionRefusedError | 1027 |
| gaierror | 369 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.94 | prefer | 22 | 0.955 | 588 |
| mheidari-all | 0.901 | prefer | 65 | 0.831 | 23162 |
| Au1rxx-base64 | 0.85 | prefer | 310 | 0.781 | 1767 |
| Surfboard-tg-mixed | 0.81 | prefer | 124 | 0.734 | 7144 |
| DeltaKronecker-all | 0.78 | prefer | 28 | 0.714 | 5603 |
| tg-oneclickvpnkeys | 0.314 | observe | 2 | 1.0 | 81 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5324 |
| Epodonios-all | 0.255 | observe | 0 | None | 7625 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9494 |

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
| DeltaKronecker-all | 0.714 | 20 | 8 | 28 |
| Surfboard-tg-mixed | 0.734 | 91 | 33 | 124 |
| Au1rxx-base64 | 0.781 | 242 | 68 | 310 |
| mheidari-all | 0.831 | 54 | 11 | 65 |
| ermaozi | 0.955 | 21 | 1 | 22 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23162 | yes | 6.56 | 0 |
| SoliSpirit-all | 9494 | yes | 3.55 | 0 |
| Epodonios-all | 7625 | yes | 2.53 | 0 |
| Surfboard-tg-mixed | 7144 | yes | 4.89 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.98 | 0 |
| barry-far-vless | 6050 | yes | 2.26 | 0 |
| Surfboard-tg-vless | 5788 | yes | 4.37 | 0 |
| DeltaKronecker-all | 5603 | yes | 6.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 1.76 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 1.54 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 300 to 30 |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 59 |
| 204 | 26 |
| cn-block | 26 |
| geo | 11 |
