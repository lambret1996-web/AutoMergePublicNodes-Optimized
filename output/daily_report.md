# AutoNodes 每日报告

生成时间：2026-10-08 18:46:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 88869 |
| 去重后节点数 | 27205 |
| TCP 可达数 | 3000 |
| 真测通过数 | 363 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27205 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 78.2 |
| geo | 1.6 |
| probe | 326.8 |
| real_test | 204.5 |
| tcp | 46.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 3 | 3 | 50.0% |
| http | 32 | 20 | 12 | 62.5% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 145 | 120 | 25 | 82.8% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 76 | 63 | 13 | 82.9% |
| vless | 201 | 140 | 61 | 69.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 35 |
| cn-block:TimeoutError | 23 |
| 204:ProxyError | 17 |
| speed:TimeoutError | 12 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 6 |
| geo:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6504 |
| ConnectionRefusedError | 979 |
| gaierror | 311 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.96 | prefer | 20 | 1.0 | 144 |
| Au1rxx-base64 | 0.909 | prefer | 316 | 0.839 | 1813 |
| mheidari-all | 0.837 | prefer | 35 | 0.771 | 23205 |
| Surfboard-tg-mixed | 0.64 | observe | 73 | 0.562 | 7187 |
| DeltaKronecker-all | 0.37 | observe | 16 | 0.312 | 5197 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5081 |
| Epodonios-all | 0.255 | observe | 0 | None | 7780 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| SoliSpirit-all | 0.025 | observe | 0 | None | 1 | 0 |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.209 | 18 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.167 | 3 | 15 | 18 |
| DeltaKronecker-all | 0.312 | 5 | 11 | 16 |
| Surfboard-tg-mixed | 0.562 | 41 | 32 | 73 |
| mheidari-all | 0.771 | 27 | 8 | 35 |
| Au1rxx-base64 | 0.839 | 265 | 51 | 316 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23205 | yes | 5.2 | 0 |
| Epodonios-all | 7780 | yes | 3.59 | 0 |
| Surfboard-tg-mixed | 7187 | yes | 4.57 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 4.32 | 0 |
| barry-far-vless | 6016 | yes | 2.39 | 0 |
| Surfboard-tg-vless | 5683 | yes | 3.91 | 0 |
| DeltaKronecker-all | 5197 | yes | 5.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 5081 | yes | 2.2 | 0 |
| mahdibland-V2RayAggregator | 4431 | yes | 3.3 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 3.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 55 |
| cn-block | 31 |
| speed | 21 |
| geo | 10 |
