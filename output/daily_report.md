# AutoNodes 每日报告

生成时间：2026-09-17 00:41:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 89626 |
| 去重后节点数 | 24571 |
| TCP 可达数 | 3000 |
| 真测通过数 | 591 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24571 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| generate | 68.5 |
| geo | 1.4 |
| probe | 394.9 |
| real_test | 611.5 |
| tcp | 41.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 17 | 12 | 5 | 70.6% |
| hysteria2 | 23 | 21 | 2 | 91.3% |
| shadowsocks | 176 | 166 | 10 | 94.3% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 12 | 8 | 4 | 66.7% |
| vless | 844 | 380 | 464 | 45.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 245 |
| geo:ClientOSError | 80 |
| speed:TimeoutError | 65 |
| speed:ClientOSError | 48 |
| cn-block:TimeoutError | 12 |
| 204:ProxyError | 10 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 8 |
| geo:ProxyError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5979 |
| ConnectionRefusedError | 915 |
| gaierror | 364 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | prefer | 293 | 0.928 | 1705 |
| Surfboard-tg-mixed | 0.763 | prefer | 99 | 0.687 | 7464 |
| ermaozi | 0.558 | observe | 11 | 0.818 | 353 |
| mheidari-all | 0.49 | observe | 181 | 0.409 | 18096 |
| DeltaKronecker-all | 0.42 | observe | 480 | 0.34 | 6081 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4234 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 140 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7947 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| DeltaKronecker-all | 0.34 | 163 | 317 | 480 |
| mheidari-all | 0.409 | 74 | 107 | 181 |
| Surfboard-tg-mixed | 0.687 | 68 | 31 | 99 |
| ermaozi | 0.818 | 9 | 2 | 11 |
| Au1rxx-base64 | 0.928 | 272 | 21 | 293 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18096 | yes | 2.81 | 0 |
| SoliSpirit-all | 9078 | yes | 3.11 | 0 |
| Epodonios-all | 7947 | yes | 3.82 | 0 |
| Surfboard-tg-mixed | 7464 | yes | 2.33 | 0 |
| barry-far-vless | 6148 | yes | 2.41 | 0 |
| DeltaKronecker-all | 6081 | yes | 3.02 | 0 |
| Surfboard-tg-vless | 5964 | yes | 2.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 1.4 | 0 |
| mahdibland-V2RayAggregator | 4234 | yes | 1.73 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.9 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 328 |
| speed | 114 |
| 204 | 22 |
| cn-block | 22 |
