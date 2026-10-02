# AutoNodes 每日报告

生成时间：2026-10-02 17:45:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 98390 |
| 去重后节点数 | 27135 |
| TCP 可达数 | 3000 |
| 真测通过数 | 414 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27135 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 74.4 |
| geo | 1.2 |
| probe | 227.2 |
| real_test | 200.5 |
| tcp | 46.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 159 | 131 | 28 | 82.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 24 | 15 | 9 | 62.5% |
| vless | 289 | 224 | 65 | 77.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 31 |
| cn-block:TimeoutError | 21 |
| speed:TimeoutError | 14 |
| 204:ProxyError | 10 |
| geo:TimeoutError | 9 |
| geo:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 3 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6302 |
| ConnectionRefusedError | 1146 |
| gaierror | 415 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.948 | prefer | 24 | 0.958 | 620 |
| Au1rxx-base64 | 0.918 | prefer | 307 | 0.85 | 1750 |
| mheidari-all | 0.826 | prefer | 57 | 0.754 | 22996 |
| Surfboard-tg-mixed | 0.769 | prefer | 117 | 0.692 | 7244 |
| DeltaKronecker-all | 0.389 | observe | 13 | 0.385 | 4981 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5276 |
| Epodonios-all | 0.255 | observe | 0 | None | 7739 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9417 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.385 | 5 | 8 | 13 |
| Surfboard-tg-mixed | 0.692 | 81 | 36 | 117 |
| mheidari-all | 0.754 | 43 | 14 | 57 |
| Au1rxx-base64 | 0.85 | 261 | 46 | 307 |
| ermaozi | 0.958 | 23 | 1 | 24 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22996 | yes | 4.26 | 0 |
| SoliSpirit-all | 9417 | yes | 2.98 | 0 |
| Epodonios-all | 7739 | yes | 4.42 | 0 |
| Surfboard-tg-mixed | 7244 | yes | 3.1 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.11 | 0 |
| barry-far-vless | 6150 | yes | 1.05 | 0 |
| Surfboard-tg-vless | 5909 | yes | 3.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 5276 | yes | 1.28 | 0 |
| DeltaKronecker-all | 4981 | yes | 4.64 | 0 |
| mahdibland-V2RayAggregator | 4310 | yes | 1.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 45 |
| cn-block | 25 |
| speed | 21 |
| geo | 16 |
