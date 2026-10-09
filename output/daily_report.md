# AutoNodes 每日报告

生成时间：2026-10-09 18:18:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98340 |
| 去重后节点数 | 27594 |
| TCP 可达数 | 3000 |
| 真测通过数 | 426 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27594 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 89.7 |
| geo | 1.4 |
| probe | 300.3 |
| real_test | 317.3 |
| tcp | 47.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 60 | 28 | 32 | 46.7% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 145 | 127 | 18 | 87.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 113 | 100 | 13 | 88.5% |
| vless | 225 | 150 | 75 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 43 |
| 204:TimeoutError | 38 |
| cn-block:TimeoutError | 21 |
| geo:ClientOSError | 11 |
| speed:ClientOSError | 8 |
| cn-block:ClientOSError | 7 |
| geo:TimeoutError | 5 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6769 |
| ConnectionRefusedError | 1024 |
| gaierror | 357 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.945 | prefer | 347 | 0.873 | 1840 |
| mheidari-all | 0.894 | prefer | 41 | 0.829 | 23183 |
| Surfboard-tg-mixed | 0.605 | observe | 99 | 0.525 | 7121 |
| DeltaKronecker-all | 0.418 | observe | 16 | 0.375 | 5154 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4984 |
| Epodonios-all | 0.255 | observe | 0 | None | 7589 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10106 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.214 | 40 | 0.175 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.175 | 7 | 33 | 40 |
| DeltaKronecker-all | 0.375 | 6 | 10 | 16 |
| Surfboard-tg-mixed | 0.525 | 52 | 47 | 99 |
| mheidari-all | 0.829 | 34 | 7 | 41 |
| Au1rxx-base64 | 0.873 | 303 | 44 | 347 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23183 | yes | 4.42 | 0 |
| SoliSpirit-all | 10106 | yes | 1.77 | 0 |
| Epodonios-all | 7589 | yes | 4.59 | 0 |
| Surfboard-tg-mixed | 7121 | yes | 3.18 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.02 | 0 |
| barry-far-vless | 5819 | yes | 1.14 | 0 |
| Surfboard-tg-vless | 5572 | yes | 2.94 | 0 |
| DeltaKronecker-all | 5154 | yes | 3.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 4984 | yes | 0.61 | 0 |
| mahdibland-V2RayAggregator | 4362 | yes | 2.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 83 |
| cn-block | 30 |
| geo | 17 |
| speed | 12 |
