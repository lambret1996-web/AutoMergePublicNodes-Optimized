# AutoNodes 每日报告

生成时间：2026-09-16 00:41:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85453 |
| 去重后节点数 | 23177 |
| TCP 可达数 | 3000 |
| 真测通过数 | 638 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23177 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 80.6 |
| geo | 1.4 |
| probe | 404.5 |
| real_test | 569.8 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 42 | 33 | 9 | 78.6% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 171 | 166 | 5 | 97.1% |
| socks | 7 | 3 | 4 | 42.9% |
| trojan | 45 | 23 | 22 | 51.1% |
| vless | 770 | 394 | 376 | 51.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 219 |
| geo:ClientOSError | 58 |
| speed:TimeoutError | 52 |
| speed:ClientOSError | 38 |
| 204:ProxyError | 15 |
| cn-block:ClientOSError | 11 |
| cn-block:TimeoutError | 11 |
| 204:TimeoutError | 9 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5253 |
| ConnectionRefusedError | 830 |
| gaierror | 422 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | prefer | 305 | 0.915 | 1577 |
| Surfboard-tg-mixed | 0.863 | prefer | 90 | 0.789 | 7589 |
| ermaozi | 0.797 | prefer | 39 | 0.795 | 406 |
| mheidari-all | 0.667 | observe | 119 | 0.588 | 16112 |
| DeltaKronecker-all | 0.449 | observe | 496 | 0.369 | 5932 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5015 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 148 |
| Epodonios-all | 0.255 | observe | 0 | None | 8039 |
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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.369 | 183 | 313 | 496 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.588 | 70 | 49 | 119 |
| Surfboard-tg-mixed | 0.789 | 71 | 19 | 90 |
| ermaozi | 0.795 | 31 | 8 | 39 |
| Au1rxx-base64 | 0.915 | 279 | 26 | 305 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16112 | yes | 4.91 | 0 |
| SoliSpirit-all | 9195 | yes | 3.04 | 0 |
| Epodonios-all | 8039 | yes | 5.55 | 0 |
| Surfboard-tg-mixed | 7589 | yes | 4.17 | 0 |
| barry-far-vless | 6357 | yes | 1.35 | 0 |
| Surfboard-tg-vless | 6098 | yes | 3.86 | 0 |
| DeltaKronecker-all | 5932 | yes | 5.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.42 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 3.2 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.13 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 277 |
| speed | 90 |
| 204 | 25 |
| cn-block | 25 |
