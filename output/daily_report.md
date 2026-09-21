# AutoNodes 每日报告

生成时间：2026-09-21 06:36:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 84788 |
| 去重后节点数 | 23352 |
| TCP 可达数 | 3000 |
| 真测通过数 | 568 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23352 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 76.3 |
| geo | 1.4 |
| probe | 231.3 |
| real_test | 347.4 |
| tcp | 39.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 42 | 31 | 11 | 73.8% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 169 | 158 | 11 | 93.5% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 68 | 46 | 22 | 67.6% |
| vless | 567 | 312 | 255 | 55.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 104 |
| geo:ClientOSError | 51 |
| speed:TimeoutError | 38 |
| 204:TimeoutError | 33 |
| speed:ClientOSError | 23 |
| 204:ProxyError | 19 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 12 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| 204:ServerDisconnectedError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5709 |
| ConnectionRefusedError | 785 |
| gaierror | 246 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.918 | prefer | 35 | 0.857 | 16285 |
| Au1rxx-base64 | 0.91 | prefer | 325 | 0.843 | 1727 |
| ermaozi | 0.697 | observe | 39 | 0.692 | 355 |
| Surfboard-tg-mixed | 0.664 | observe | 301 | 0.585 | 7246 |
| DeltaKronecker-all | 0.448 | observe | 150 | 0.367 | 6092 |
| tg-oneclickvpnkeys | 0.404 | observe | 4 | 1.0 | 92 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7661 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9052 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-ScrapeCategorize-Vless | 0.144 | 7 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ninja-vless | 0.2 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 7 | 7 |
| ninja-vless | 0.143 | 1 | 6 | 7 |
| DeltaKronecker-all | 0.367 | 55 | 95 | 150 |
| Surfboard-tg-mixed | 0.585 | 176 | 125 | 301 |
| ermaozi | 0.692 | 27 | 12 | 39 |
| Au1rxx-base64 | 0.843 | 274 | 51 | 325 |
| mheidari-all | 0.857 | 30 | 5 | 35 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16285 | yes | 3.39 | 0 |
| SoliSpirit-all | 9052 | yes | 2.63 | 0 |
| Epodonios-all | 7661 | yes | 2.08 | 0 |
| Surfboard-tg-mixed | 7246 | yes | 2.65 | 0 |
| DeltaKronecker-all | 6092 | yes | 3.03 | 0 |
| barry-far-vless | 6061 | yes | 1.44 | 0 |
| Surfboard-tg-vless | 5845 | yes | 3.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 1.22 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 1.88 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.3 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 156 |
| speed | 61 |
| 204 | 58 |
| cn-block | 27 |
