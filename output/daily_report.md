# AutoNodes 每日报告

生成时间：2026-09-10 12:35:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 91588 |
| 去重后节点数 | 24229 |
| TCP 可达数 | 3000 |
| 真测通过数 | 473 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24229 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 76.9 |
| geo | 1.4 |
| probe | 269.4 |
| real_test | 352.4 |
| tcp | 41.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 54 | 41 | 13 | 75.9% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 167 | 154 | 13 | 92.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 54 | 40 | 14 | 74.1% |
| vless | 280 | 214 | 66 | 76.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 23 |
| 204:ProxyError | 19 |
| cn-block:ClientOSError | 14 |
| cn-block:TimeoutError | 14 |
| 204:TimeoutError | 13 |
| speed:ClientOSError | 9 |
| speed:TimeoutError | 7 |
| geo:TimeoutError | 6 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5709 |
| ConnectionRefusedError | 927 |
| gaierror | 402 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.948 | prefer | 271 | 0.886 | 1629 |
| mheidari-all | 0.904 | prefer | 72 | 0.833 | 19290 |
| Surfboard-tg-mixed | 0.821 | prefer | 168 | 0.744 | 7439 |
| ermaozi | 0.763 | prefer | 53 | 0.755 | 449 |
| DeltaKronecker-all | 0.425 | observe | 15 | 0.4 | 5853 |
| ermaozi-get_subscribe | 0.274 | observe | 1 | 1.0 | 469 |
| tg-oneclickvpnkeys | 0.264 | observe | 1 | 1.0 | 214 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7808 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| DeltaKronecker-all | 0.4 | 6 | 9 | 15 |
| Surfboard-tg-mixed | 0.744 | 125 | 43 | 168 |
| ermaozi | 0.755 | 40 | 13 | 53 |
| mheidari-all | 0.833 | 60 | 12 | 72 |
| Au1rxx-base64 | 0.886 | 240 | 31 | 271 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19290 | yes | 4.23 | 0 |
| SoliSpirit-all | 9102 | yes | 1.34 | 0 |
| Epodonios-all | 7808 | yes | 0.32 | 0 |
| Surfboard-tg-mixed | 7439 | yes | 3.01 | 0 |
| barry-far-vless | 6215 | yes | 0.72 | 0 |
| Surfboard-tg-vless | 6025 | yes | 2.84 | 0 |
| DeltaKronecker-all | 5853 | yes | 4.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 1.11 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 2.55 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.58 | 0 |

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
| 204 | 33 |
| geo | 30 |
| cn-block | 29 |
| speed | 16 |
