# AutoNodes 每日报告

生成时间：2026-09-23 12:32:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96830 |
| 去重后节点数 | 26517 |
| TCP 可达数 | 3000 |
| 真测通过数 | 443 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26517 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 111.3 |
| geo | 1.7 |
| probe | 279.4 |
| real_test | 161.6 |
| tcp | 42.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 71 | 49 | 22 | 69.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 176 | 163 | 13 | 92.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 17 | 13 | 4 | 76.5% |
| vless | 302 | 193 | 109 | 63.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 35 |
| 204:ProxyError | 29 |
| cn-block:ClientOSError | 28 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 16 |
| geo:TimeoutError | 10 |
| speed:ClientOSError | 6 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5731 |
| ConnectionRefusedError | 967 |
| gaierror | 366 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.993 | prefer | 237 | 0.932 | 1599 |
| Surfboard-tg-mixed | 0.801 | prefer | 138 | 0.725 | 7036 |
| ermaozi | 0.76 | prefer | 57 | 0.754 | 346 |
| mheidari-all | 0.576 | observe | 139 | 0.496 | 22242 |
| ermaozi-get_subscribe | 0.324 | observe | 13 | 0.385 | 372 |
| DeltaKronecker-all | 0.32 | observe | 4 | 0.5 | 6471 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 117 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5131 |
| Epodonios-all | 0.255 | observe | 0 | None | 7633 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.385 | 5 | 8 | 13 |
| mheidari-all | 0.496 | 69 | 70 | 139 |
| DeltaKronecker-all | 0.5 | 2 | 2 | 4 |
| roosterkid-openproxylist-v2ray | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.725 | 100 | 38 | 138 |
| ermaozi | 0.754 | 43 | 14 | 57 |
| Au1rxx-base64 | 0.932 | 221 | 16 | 237 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22242 | yes | 6.66 | 0 |
| SoliSpirit-all | 9052 | yes | 2.59 | 0 |
| Epodonios-all | 7633 | yes | 4.51 | 0 |
| Surfboard-tg-mixed | 7036 | yes | 3.97 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.16 | 0 |
| DeltaKronecker-all | 6471 | yes | 5.77 | 0 |
| barry-far-vless | 5975 | yes | 0.72 | 0 |
| Surfboard-tg-vless | 5755 | yes | 4.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 0.5 | 0 |
| mahdibland-V2RayAggregator | 4187 | yes | 3.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 48 |
| 204 | 46 |
| geo | 46 |
| speed | 11 |
