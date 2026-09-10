# AutoNodes 每日报告

生成时间：2026-09-10 06:35:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 87973 |
| 去重后节点数 | 23200 |
| TCP 可达数 | 3000 |
| 真测通过数 | 543 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23200 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 80.6 |
| geo | 1.4 |
| probe | 285.6 |
| real_test | 314.6 |
| tcp | 40.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 55 | 41 | 14 | 74.5% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 151 | 140 | 11 | 92.7% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 59 | 55 | 4 | 93.2% |
| vless | 401 | 282 | 119 | 70.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 31 |
| 204:ProxyError | 22 |
| cn-block:TimeoutError | 19 |
| speed:TimeoutError | 18 |
| 204:TimeoutError | 16 |
| geo:TimeoutError | 16 |
| cn-block:ClientOSError | 13 |
| speed:ClientOSError | 8 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5823 |
| ConnectionRefusedError | 919 |
| gaierror | 292 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.953 | prefer | 277 | 0.888 | 1684 |
| Surfboard-tg-mixed | 0.85 | prefer | 181 | 0.773 | 7346 |
| ermaozi | 0.768 | prefer | 54 | 0.759 | 449 |
| mheidari-all | 0.725 | prefer | 139 | 0.647 | 16259 |
| DeltaKronecker-all | 0.725 | prefer | 29 | 0.655 | 5187 |
| xiaoji235-airport-v2ray-all | 0.465 | observe | 7 | 0.714 | 3508 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| Epodonios-all | 0.255 | observe | 0 | None | 7921 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8976 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.647 | 90 | 49 | 139 |
| DeltaKronecker-all | 0.655 | 19 | 10 | 29 |
| xiaoji235-airport-v2ray-all | 0.714 | 5 | 2 | 7 |
| ermaozi | 0.759 | 41 | 13 | 54 |
| Surfboard-tg-mixed | 0.773 | 140 | 41 | 181 |
| Au1rxx-base64 | 0.888 | 246 | 31 | 277 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16259 | yes | 5.74 | 0 |
| SoliSpirit-all | 8976 | yes | 1.78 | 0 |
| Epodonios-all | 7921 | yes | 3.17 | 0 |
| Surfboard-tg-mixed | 7346 | yes | 5.08 | 0 |
| barry-far-vless | 6344 | yes | 1.23 | 0 |
| Surfboard-tg-vless | 5990 | yes | 4.25 | 0 |
| DeltaKronecker-all | 5187 | yes | 4.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 1.04 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 2.9 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.85 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 49 |
| 204 | 43 |
| cn-block | 33 |
| speed | 27 |
