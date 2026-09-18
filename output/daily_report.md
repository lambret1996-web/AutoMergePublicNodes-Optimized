# AutoNodes 每日报告

生成时间：2026-09-18 12:31:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83287 |
| 去重后节点数 | 22995 |
| TCP 可达数 | 3000 |
| 真测通过数 | 393 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22995 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.6 |
| generate | 84.3 |
| geo | 1.3 |
| probe | 241.0 |
| real_test | 243.3 |
| tcp | 38.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 34 | 10 | 77.3% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 167 | 154 | 13 | 92.2% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 18 | 6 | 12 | 33.3% |
| vless | 305 | 182 | 123 | 59.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 47 |
| geo:ClientOSError | 36 |
| 204:TimeoutError | 20 |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 11 |
| speed:ClientOSError | 10 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5458 |
| ConnectionRefusedError | 814 |
| gaierror | 303 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.969 | prefer | 34 | 0.912 | 15778 |
| Au1rxx-base64 | 0.914 | prefer | 230 | 0.852 | 1624 |
| Surfboard-tg-mixed | 0.756 | prefer | 143 | 0.678 | 7294 |
| ermaozi | 0.754 | prefer | 44 | 0.75 | 378 |
| DeltaKronecker-all | 0.436 | observe | 99 | 0.354 | 6040 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5076 |
| Epodonios-all | 0.255 | observe | 0 | None | 7751 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8732 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.354 | 35 | 64 | 99 |
| Surfboard-tg-mixed | 0.678 | 97 | 46 | 143 |
| ermaozi | 0.75 | 33 | 11 | 44 |
| Au1rxx-base64 | 0.852 | 196 | 34 | 230 |
| mheidari-all | 0.912 | 31 | 3 | 34 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15778 | yes | 2.41 | 0 |
| SoliSpirit-all | 8732 | yes | 1.87 | 0 |
| Epodonios-all | 7751 | yes | 2.52 | 0 |
| Surfboard-tg-mixed | 7294 | yes | 2.02 | 0 |
| DeltaKronecker-all | 6040 | yes | 2.59 | 0 |
| barry-far-vless | 5979 | yes | 1.02 | 0 |
| Surfboard-tg-vless | 5763 | yes | 1.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 1.32 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 1.43 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.05 | 0 |

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
| geo | 83 |
| 204 | 40 |
| cn-block | 21 |
| speed | 17 |
