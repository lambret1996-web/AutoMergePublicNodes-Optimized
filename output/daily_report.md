# AutoNodes 每日报告

生成时间：2026-10-16 16:29:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99087 |
| 去重后节点数 | 27699 |
| TCP 可达数 | 3000 |
| 真测通过数 | 387 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27699 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 80.1 |
| geo | 1.3 |
| probe | 401.1 |
| real_test | 302.1 |
| tcp | 48.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 61 | 26 | 35 | 42.6% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 143 | 123 | 20 | 86.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 86 | 53 | 33 | 61.6% |
| vless | 277 | 170 | 107 | 61.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 62 |
| 204:ProxyError | 47 |
| cn-block:TimeoutError | 24 |
| speed:TimeoutError | 17 |
| speed:ClientOSError | 13 |
| geo:TimeoutError | 13 |
| cn-block:ClientOSError | 7 |
| geo:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7029 |
| ConnectionRefusedError | 1038 |
| OSError | 237 |
| gaierror | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.822 | prefer | 444 | 0.743 | 1991 |
| DeltaKronecker-all | 0.509 | observe | 40 | 0.425 | 4946 |
| ermaozi | 0.444 | observe | 60 | 0.417 | 618 |
| Surfboard-tg-mixed | 0.376 | observe | 25 | 0.28 | 7090 |
| mheidari-all | 0.372 | observe | 9 | 0.444 | 23974 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| ermaozi-get_subscribe | 0.274 | observe | 1 | 1.0 | 484 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 79 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.28 | 7 | 18 | 25 |
| ermaozi | 0.417 | 25 | 35 | 60 |
| DeltaKronecker-all | 0.425 | 17 | 23 | 40 |
| mheidari-all | 0.444 | 4 | 5 | 9 |
| Au1rxx-base64 | 0.743 | 330 | 114 | 444 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23974 | yes | 4.63 | 0 |
| SoliSpirit-all | 9917 | yes | 2.86 | 0 |
| Epodonios-all | 7602 | yes | 3.6 | 0 |
| Surfboard-tg-mixed | 7090 | yes | 3.19 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.93 | 0 |
| barry-far-vless | 5822 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 5572 | yes | 2.61 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 1.77 | 0 |
| DeltaKronecker-all | 4946 | yes | 3.3 | 0 |
| mahdibland-V2RayAggregator | 4265 | yes | 1.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 113 |
| cn-block | 34 |
| speed | 31 |
| geo | 18 |
