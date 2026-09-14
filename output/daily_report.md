# AutoNodes 每日报告

生成时间：2026-09-14 18:29:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 84821 |
| 去重后节点数 | 22987 |
| TCP 可达数 | 3000 |
| 真测通过数 | 412 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22987 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 68.6 |
| geo | 1.4 |
| probe | 272.5 |
| real_test | 212.3 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 22 | 22 | 50.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 150 | 139 | 11 | 92.7% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 11 | 5 | 6 | 45.5% |
| vless | 286 | 225 | 61 | 78.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 24 |
| 204:TimeoutError | 22 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 14 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 4 |
| speed:ClientOSError | 4 |
| 204:ClientOSError | 4 |
| speed:TimeoutError | 2 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5330 |
| ConnectionRefusedError | 850 |
| gaierror | 357 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | prefer | 293 | 0.935 | 1619 |
| mheidari-all | 0.8 | prefer | 48 | 0.729 | 15899 |
| DeltaKronecker-all | 0.734 | prefer | 18 | 0.722 | 5972 |
| Surfboard-tg-mixed | 0.702 | prefer | 109 | 0.624 | 7482 |
| ermaozi | 0.61 | observe | 35 | 0.6 | 393 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 149 |
| Epodonios-all | 0.255 | observe | 0 | None | 7933 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9209 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6061 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.075 | 9 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 9 | 9 |
| ermaozi | 0.6 | 21 | 14 | 35 |
| Surfboard-tg-mixed | 0.624 | 68 | 41 | 109 |
| DeltaKronecker-all | 0.722 | 13 | 5 | 18 |
| mheidari-all | 0.729 | 35 | 13 | 48 |
| Au1rxx-base64 | 0.935 | 274 | 19 | 293 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15899 | yes | 2.85 | 0 |
| SoliSpirit-all | 9209 | yes | 2.72 | 0 |
| Epodonios-all | 7933 | yes | 2.49 | 0 |
| Surfboard-tg-mixed | 7482 | yes | 4.21 | 0 |
| barry-far-vless | 6293 | yes | 2.09 | 0 |
| Surfboard-tg-vless | 6061 | yes | 3.39 | 0 |
| DeltaKronecker-all | 5972 | yes | 3.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 2.24 | 0 |
| mahdibland-V2RayAggregator | 4176 | yes | 0.97 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.78 | 0 |

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
| 204 | 50 |
| cn-block | 25 |
| geo | 22 |
| speed | 6 |
