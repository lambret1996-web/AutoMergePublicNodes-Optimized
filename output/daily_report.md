# AutoNodes 每日报告

生成时间：2026-10-10 05:07:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97894 |
| 去重后节点数 | 27735 |
| TCP 可达数 | 3000 |
| 真测通过数 | 546 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27735 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 71.4 |
| geo | 1.4 |
| probe | 350.9 |
| real_test | 604.9 |
| tcp | 47.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 4 | 3 | 57.1% |
| http | 45 | 37 | 8 | 82.2% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 164 | 151 | 13 | 92.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 137 | 125 | 12 | 91.2% |
| vless | 500 | 206 | 294 | 41.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 156 |
| speed:TimeoutError | 62 |
| geo:ClientOSError | 31 |
| 204:ProxyError | 24 |
| speed:ClientOSError | 23 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6806 |
| ConnectionRefusedError | 1016 |
| gaierror | 266 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | prefer | 366 | 0.913 | 1786 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.875 | prefer | 71 | 0.803 | 7155 |
| ermaozi-get_subscribe | 0.626 | observe | 28 | 0.607 | 653 |
| mheidari-all | 0.382 | observe | 382 | 0.301 | 23395 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4984 |
| Epodonios-all | 0.255 | observe | 0 | None | 7634 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9590 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5643 |

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
| downweight | DeltaKronecker-all | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.0 | 0 | 5 | 5 |
| mheidari-all | 0.301 | 115 | 267 | 382 |
| ermaozi-get_subscribe | 0.607 | 17 | 11 | 28 |
| Surfboard-tg-mixed | 0.803 | 57 | 14 | 71 |
| Au1rxx-base64 | 0.913 | 334 | 32 | 366 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23395 | yes | 3.14 | 0 |
| SoliSpirit-all | 9590 | yes | 1.62 | 0 |
| Epodonios-all | 7634 | yes | 2.25 | 0 |
| Surfboard-tg-mixed | 7155 | yes | 1.57 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.8 | 0 |
| barry-far-vless | 5793 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 5643 | yes | 2.56 | 0 |
| DeltaKronecker-all | 5154 | yes | 3.77 | 0 |
| 10ium-ScrapeCategorize-Vless | 4984 | yes | 1.01 | 0 |
| mahdibland-V2RayAggregator | 4346 | yes | 2.0 | 0 |

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
| geo | 187 |
| speed | 85 |
| 204 | 35 |
| cn-block | 25 |
