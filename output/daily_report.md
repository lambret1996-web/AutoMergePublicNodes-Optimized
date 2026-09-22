# AutoNodes 每日报告

生成时间：2026-09-22 18:30:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87981 |
| 去重后节点数 | 25371 |
| TCP 可达数 | 3000 |
| 真测通过数 | 393 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25371 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 77.6 |
| geo | 1.4 |
| probe | 245.7 |
| real_test | 182.4 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 30 | 20 | 10 | 66.7% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 155 | 140 | 15 | 90.3% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 17 | 15 | 2 | 88.2% |
| vless | 355 | 199 | 156 | 56.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 55 |
| geo:ClientOSError | 34 |
| cn-block:TimeoutError | 24 |
| 204:TimeoutError | 20 |
| 204:ProxyError | 19 |
| cn-block:ClientOSError | 14 |
| geo:TimeoutError | 9 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6122 |
| ConnectionRefusedError | 939 |
| gaierror | 268 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.87 | prefer | 301 | 0.804 | 1703 |
| DeltaKronecker-all | 0.747 | prefer | 25 | 0.68 | 6324 |
| ermaozi | 0.727 | prefer | 26 | 0.731 | 325 |
| mheidari-all | 0.677 | observe | 65 | 0.6 | 16289 |
| Surfboard-tg-mixed | 0.531 | observe | 142 | 0.451 | 7076 |
| mahdibland-V2RayAggregator | 0.519 | observe | 5 | 1.0 | 4252 |
| xiaoji235-airport-v2ray-all | 0.418 | observe | 10 | 0.5 | 4242 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4915 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 117 |
| Epodonios-all | 0.255 | observe | 0 | None | 7534 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 3 | 3 |
| Surfboard-tg-mixed | 0.451 | 64 | 78 | 142 |
| xiaoji235-airport-v2ray-all | 0.5 | 5 | 5 | 10 |
| mheidari-all | 0.6 | 39 | 26 | 65 |
| DeltaKronecker-all | 0.68 | 17 | 8 | 25 |
| ermaozi | 0.731 | 19 | 7 | 26 |
| Au1rxx-base64 | 0.804 | 242 | 59 | 301 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16289 | yes | 4.96 | 0 |
| SoliSpirit-all | 8848 | yes | 4.89 | 0 |
| Epodonios-all | 7534 | yes | 3.63 | 0 |
| Surfboard-tg-mixed | 7076 | yes | 5.52 | 0 |
| DeltaKronecker-all | 6324 | yes | 5.84 | 0 |
| barry-far-vless | 6010 | yes | 2.1 | 0 |
| Surfboard-tg-vless | 5712 | yes | 4.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 2.66 | 0 |
| mahdibland-V2RayAggregator | 4252 | yes | 0.16 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.21 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 62 |
| geo | 43 |
| 204 | 42 |
| cn-block | 40 |
