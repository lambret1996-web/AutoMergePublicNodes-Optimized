# AutoNodes 每日报告

生成时间：2026-09-16 06:37:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85286 |
| 去重后节点数 | 22914 |
| TCP 可达数 | 3000 |
| 真测通过数 | 509 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22914 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 87.3 |
| geo | 1.5 |
| probe | 300.7 |
| real_test | 445.1 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 71 | 49 | 22 | 69.0% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 161 | 149 | 12 | 92.5% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 31 | 21 | 10 | 67.7% |
| vless | 564 | 266 | 298 | 47.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 135 |
| geo:ClientOSError | 59 |
| speed:TimeoutError | 36 |
| 204:ProxyError | 31 |
| speed:ClientOSError | 25 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 18 |
| cn-block:ClientOSError | 13 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5213 |
| ConnectionRefusedError | 833 |
| gaierror | 381 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.913 | prefer | 284 | 0.849 | 1683 |
| mheidari-all | 0.768 | prefer | 91 | 0.692 | 16114 |
| ermaozi | 0.766 | prefer | 54 | 0.759 | 407 |
| Surfboard-tg-mixed | 0.686 | observe | 178 | 0.607 | 7549 |
| ermaozi-get_subscribe | 0.485 | observe | 18 | 0.5 | 438 |
| DeltaKronecker-all | 0.286 | observe | 226 | 0.204 | 5932 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 178 |
| Epodonios-all | 0.255 | observe | 0 | None | 8003 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8866 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.204 | 46 | 180 | 226 |
| ermaozi-get_subscribe | 0.5 | 9 | 9 | 18 |
| Surfboard-tg-mixed | 0.607 | 108 | 70 | 178 |
| mheidari-all | 0.692 | 63 | 28 | 91 |
| ermaozi | 0.759 | 41 | 13 | 54 |
| Au1rxx-base64 | 0.849 | 241 | 43 | 284 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16114 | yes | 4.95 | 0 |
| SoliSpirit-all | 8866 | yes | 3.11 | 0 |
| Epodonios-all | 8003 | yes | 5.19 | 0 |
| Surfboard-tg-mixed | 7549 | yes | 4.01 | 0 |
| barry-far-vless | 6340 | yes | 1.14 | 0 |
| Surfboard-tg-vless | 6134 | yes | 4.22 | 0 |
| DeltaKronecker-all | 5932 | yes | 4.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 2.02 | 0 |
| mahdibland-V2RayAggregator | 4206 | yes | 3.21 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 195 |
| speed | 61 |
| 204 | 54 |
| cn-block | 37 |
