# AutoNodes 每日报告

生成时间：2026-09-21 00:39:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83607 |
| 去重后节点数 | 23524 |
| TCP 可达数 | 3000 |
| 真测通过数 | 701 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23524 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 72.3 |
| geo | 1.5 |
| probe | 313.6 |
| real_test | 464.1 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 32 | 27 | 5 | 84.4% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 149 | 144 | 5 | 96.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 11 | 10 | 1 | 90.9% |
| vless | 906 | 502 | 404 | 55.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 163 |
| geo:ClientOSError | 84 |
| speed:TimeoutError | 57 |
| speed:ClientOSError | 54 |
| cn-block:ClientOSError | 16 |
| 204:TimeoutError | 14 |
| 204:ProxyError | 12 |
| cn-block:TimeoutError | 9 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5229 |
| ConnectionRefusedError | 820 |
| gaierror | 419 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.963 | prefer | 327 | 0.905 | 1515 |
| ermaozi | 0.87 | prefer | 26 | 0.885 | 314 |
| Surfboard-tg-mixed | 0.703 | prefer | 242 | 0.624 | 7207 |
| DeltaKronecker-all | 0.545 | observe | 409 | 0.465 | 6092 |
| mheidari-all | 0.448 | observe | 93 | 0.366 | 16054 |
| tg-oneclickvpnkeys | 0.361 | observe | 3 | 1.0 | 74 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4315 |
| Au1rxx-clash | 0.322 | observe | 1 | 1.0 | 1670 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7665 |

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
| downweight | 10ium-ScrapeCategorize-Vless | 0.193 | 10 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.1 | 1 | 9 | 10 |
| mheidari-all | 0.366 | 34 | 59 | 93 |
| DeltaKronecker-all | 0.465 | 190 | 219 | 409 |
| Surfboard-tg-mixed | 0.624 | 151 | 91 | 242 |
| ermaozi | 0.885 | 23 | 3 | 26 |
| Au1rxx-base64 | 0.905 | 296 | 31 | 327 |
| Au1rxx-clash | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16054 | yes | 2.93 | 0 |
| SoliSpirit-all | 8799 | yes | 2.0 | 0 |
| Epodonios-all | 7665 | yes | 3.46 | 0 |
| Surfboard-tg-mixed | 7207 | yes | 2.39 | 0 |
| DeltaKronecker-all | 6092 | yes | 3.36 | 0 |
| barry-far-vless | 5983 | yes | 1.03 | 0 |
| Surfboard-tg-vless | 5768 | yes | 3.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 0.6 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 2.1 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 249 |
| speed | 111 |
| 204 | 31 |
| cn-block | 27 |
