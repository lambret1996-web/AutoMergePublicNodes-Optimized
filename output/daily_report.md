# AutoNodes 每日报告

生成时间：2026-09-08 06:28:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 91344 |
| 去重后节点数 | 25185 |
| TCP 可达数 | 3000 |
| 真测通过数 | 601 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25185 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 18.6 |
| generate | 35.8 |
| geo | 1.5 |
| probe | 88.1 |
| real_test | 150.6 |
| tcp | 41.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 5 | 0 | 100.0% |
| http | 72 | 72 | 0 | 100.0% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 178 | 165 | 13 | 92.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 45 | 24 | 21 | 53.3% |
| vless | 574 | 313 | 261 | 54.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 62 |
| cn-block:ClientOSError | 62 |
| speed:TimeoutError | 42 |
| geo:ClientOSError | 39 |
| speed:ClientOSError | 32 |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 21 |
| 204:ProxyError | 9 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5944 |
| ConnectionRefusedError | 956 |
| gaierror | 367 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 53 | 1.0 | 450 |
| ermaozi-get_subscribe | 0.94 | prefer | 19 | 1.0 | 470 |
| Au1rxx-base64 | 0.932 | prefer | 352 | 0.861 | 1834 |
| Surfboard-tg-mixed | 0.818 | prefer | 185 | 0.741 | 7392 |
| tg-oneclickvpnkeys | 0.447 | observe | 5 | 1.0 | 199 |
| mheidari-all | 0.377 | observe | 284 | 0.296 | 22287 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 6417 |
| Epodonios-all | 0.255 | observe | 0 | None | 7862 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.296 | 84 | 200 | 284 |
| Surfboard-tg-mixed | 0.741 | 137 | 48 | 185 |
| Au1rxx-base64 | 0.861 | 303 | 49 | 352 |
| tg-oneclickvpnkeys | 1.0 | 5 | 0 | 5 |
| ermaozi-get_subscribe | 1.0 | 19 | 0 | 19 |
| ermaozi | 1.0 | 53 | 0 | 53 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22287 | yes | 6.33 | 0 |
| SoliSpirit-all | 8456 | yes | 6.15 | 0 |
| Epodonios-all | 7862 | yes | 6.52 | 0 |
| Surfboard-tg-mixed | 7392 | yes | 4.03 | 0 |
| DeltaKronecker-all | 6417 | yes | 4.32 | 0 |
| barry-far-vless | 6415 | yes | 2.58 | 0 |
| Surfboard-tg-vless | 6186 | yes | 5.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 2.34 | 0 |
| mahdibland-V2RayAggregator | 4209 | yes | 3.15 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 101 |
| cn-block | 86 |
| speed | 74 |
| 204 | 38 |
