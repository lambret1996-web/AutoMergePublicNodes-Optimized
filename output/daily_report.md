# AutoNodes 每日报告

生成时间：2026-09-15 00:47:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 90248 |
| 去重后节点数 | 25751 |
| TCP 可达数 | 3000 |
| 真测通过数 | 638 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25751 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 86.8 |
| geo | 1.4 |
| probe | 464.2 |
| real_test | 722.8 |
| tcp | 41.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 35 | 22 | 13 | 62.9% |
| hysteria2 | 26 | 21 | 5 | 80.8% |
| shadowsocks | 177 | 169 | 8 | 95.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 8 | 6 | 2 | 75.0% |
| vless | 1103 | 418 | 685 | 37.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 273 |
| geo:ClientOSError | 106 |
| speed:TimeoutError | 105 |
| speed:ClientOSError | 79 |
| cn-block:ClientOSError | 75 |
| 204:ProxyError | 30 |
| cn-block:TimeoutError | 26 |
| 204:TimeoutError | 14 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5828 |
| ConnectionRefusedError | 953 |
| gaierror | 450 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.921 | prefer | 354 | 0.856 | 1668 |
| Surfboard-tg-mixed | 0.753 | prefer | 102 | 0.676 | 7572 |
| ermaozi | 0.61 | observe | 35 | 0.6 | 393 |
| DeltaKronecker-all | 0.542 | observe | 154 | 0.461 | 5972 |
| mheidari-all | 0.324 | observe | 704 | 0.243 | 21472 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 135 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4914 |
| Epodonios-all | 0.255 | observe | 0 | None | 8068 |

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
| mheidari-all | 0.243 | 171 | 533 | 704 |
| DeltaKronecker-all | 0.461 | 71 | 83 | 154 |
| ermaozi | 0.6 | 21 | 14 | 35 |
| Surfboard-tg-mixed | 0.676 | 69 | 33 | 102 |
| Au1rxx-base64 | 0.856 | 303 | 51 | 354 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21472 | yes | 5.15 | 0 |
| SoliSpirit-all | 8761 | yes | 2.97 | 0 |
| Epodonios-all | 8068 | yes | 4.56 | 0 |
| Surfboard-tg-mixed | 7572 | yes | 3.49 | 0 |
| barry-far-vless | 6322 | yes | 0.8 | 0 |
| Surfboard-tg-vless | 6105 | yes | 4.01 | 0 |
| DeltaKronecker-all | 5972 | yes | 4.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 0.34 | 0 |
| mahdibland-V2RayAggregator | 4099 | yes | 1.39 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.91 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 379 |
| speed | 185 |
| cn-block | 103 |
| 204 | 48 |
