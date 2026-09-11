# AutoNodes 每日报告

生成时间：2026-09-11 00:37:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83456 |
| 去重后节点数 | 22993 |
| TCP 可达数 | 3000 |
| 真测通过数 | 514 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22993 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 80.1 |
| geo | 1.4 |
| probe | 285.3 |
| real_test | 329.1 |
| tcp | 39.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 22 | 3 | 88.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 167 | 163 | 4 | 97.6% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 33 | 31 | 2 | 93.9% |
| vless | 451 | 279 | 172 | 61.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 41 |
| geo:TimeoutError | 41 |
| speed:TimeoutError | 40 |
| speed:ClientOSError | 19 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 9 |
| 204:ProxyError | 8 |
| 204:TimeoutError | 8 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5520 |
| ConnectionRefusedError | 896 |
| gaierror | 384 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.955 | prefer | 296 | 0.895 | 1552 |
| Surfboard-tg-mixed | 0.832 | prefer | 204 | 0.755 | 7329 |
| ermaozi | 0.824 | prefer | 24 | 0.833 | 405 |
| mheidari-all | 0.571 | observe | 104 | 0.49 | 15770 |
| DeltaKronecker-all | 0.419 | observe | 57 | 0.333 | 5853 |
| Epodonios-all | 0.335 | observe | 1 | 1.0 | 7698 |
| tg-oneclickvpnkeys | 0.318 | observe | 2 | 1.0 | 165 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8841 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-ScrapeCategorize-Vless | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 5 | 5 |
| ninja-vless | 0.25 | 1 | 3 | 4 |
| DeltaKronecker-all | 0.333 | 19 | 38 | 57 |
| mheidari-all | 0.49 | 51 | 53 | 104 |
| Surfboard-tg-mixed | 0.755 | 154 | 50 | 204 |
| ermaozi | 0.833 | 20 | 4 | 24 |
| Au1rxx-base64 | 0.895 | 265 | 31 | 296 |
| Epodonios-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15770 | yes | 3.47 | 0 |
| SoliSpirit-all | 8841 | yes | 3.23 | 0 |
| Epodonios-all | 7698 | yes | 2.37 | 0 |
| Surfboard-tg-mixed | 7329 | yes | 2.7 | 0 |
| barry-far-vless | 6066 | yes | 2.29 | 0 |
| Surfboard-tg-vless | 5926 | yes | 3.14 | 0 |
| DeltaKronecker-all | 5853 | yes | 3.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 2.16 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 2.22 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 84 |
| speed | 59 |
| cn-block | 27 |
| 204 | 16 |
