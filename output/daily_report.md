# AutoNodes 每日报告

生成时间：2026-09-27 21:22:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96200 |
| 去重后节点数 | 26758 |
| TCP 可达数 | 3000 |
| 真测通过数 | 328 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26758 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 76.7 |
| geo | 1.4 |
| probe | 234.9 |
| real_test | 124.9 |
| tcp | 43.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 35 | 19 | 16 | 54.3% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 172 | 156 | 16 | 90.7% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 8 | 6 | 2 | 75.0% |
| vless | 149 | 124 | 25 | 83.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 16 |
| 204:ProxyConnectionError | 12 |
| 204:TimeoutError | 8 |
| geo:TimeoutError | 8 |
| 204:ProxyError | 6 |
| speed:TimeoutError | 3 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5761 |
| ConnectionRefusedError | 959 |
| gaierror | 383 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.966 | prefer | 77 | 0.896 | 22680 |
| Surfboard-tg-mixed | 0.95 | prefer | 98 | 0.878 | 7018 |
| Au1rxx-base64 | 0.941 | prefer | 174 | 0.879 | 1652 |
| ermaozi | 0.539 | observe | 34 | 0.529 | 289 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| tg-oneclickvpnkeys | 0.256 | observe | 1 | 1.0 | 13 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7540 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9353 |

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
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.529 | 18 | 16 | 34 |
| Surfboard-tg-mixed | 0.878 | 86 | 12 | 98 |
| Au1rxx-base64 | 0.879 | 153 | 21 | 174 |
| mheidari-all | 0.896 | 69 | 8 | 77 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22680 | yes | 6.88 | 0 |
| SoliSpirit-all | 9353 | yes | 5.1 | 0 |
| Epodonios-all | 7540 | yes | 5.14 | 0 |
| Surfboard-tg-mixed | 7018 | yes | 6.0 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.89 | 0 |
| barry-far-vless | 5823 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 5592 | yes | 3.71 | 0 |
| DeltaKronecker-all | 5466 | yes | 5.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 0.93 | 0 |
| mahdibland-V2RayAggregator | 4185 | yes | 3.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 26 |
| cn-block | 20 |
| geo | 9 |
| speed | 6 |
