# AutoNodes 每日报告

生成时间：2026-09-12 00:34:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83057 |
| 去重后节点数 | 23305 |
| TCP 可达数 | 3000 |
| 真测通过数 | 507 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23305 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 85.7 |
| geo | 1.5 |
| probe | 238.1 |
| real_test | 295.1 |
| tcp | 39.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 21 | 8 | 13 | 38.1% |
| hysteria2 | 27 | 25 | 2 | 92.6% |
| shadowsocks | 185 | 173 | 12 | 93.5% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 76 | 40 | 36 | 52.6% |
| vless | 403 | 261 | 142 | 64.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 77 |
| geo:ClientOSError | 48 |
| 204:ProxyError | 18 |
| speed:ClientOSError | 17 |
| cn-block:ClientOSError | 16 |
| cn-block:TimeoutError | 10 |
| speed:TimeoutError | 8 |
| 204:TimeoutError | 6 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4871 |
| ConnectionRefusedError | 889 |
| gaierror | 537 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | prefer | 297 | 0.923 | 1613 |
| mheidari-all | 0.886 | prefer | 60 | 0.817 | 15581 |
| Surfboard-tg-mixed | 0.739 | prefer | 209 | 0.66 | 7263 |
| ermaozi | 0.409 | observe | 15 | 0.467 | 377 |
| DeltaKronecker-all | 0.382 | observe | 124 | 0.298 | 6070 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 194 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7719 |
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
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.084 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 6 | 6 |
| DeltaKronecker-all | 0.298 | 37 | 87 | 124 |
| ermaozi | 0.467 | 7 | 8 | 15 |
| Surfboard-tg-mixed | 0.66 | 138 | 71 | 209 |
| mheidari-all | 0.817 | 49 | 11 | 60 |
| Au1rxx-base64 | 0.923 | 274 | 23 | 297 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15581 | yes | 5.33 | 0 |
| SoliSpirit-all | 8492 | yes | 1.97 | 0 |
| Epodonios-all | 7719 | yes | 3.75 | 0 |
| Surfboard-tg-mixed | 7263 | yes | 3.41 | 0 |
| barry-far-vless | 6106 | yes | 1.51 | 0 |
| DeltaKronecker-all | 6070 | yes | 5.27 | 0 |
| Surfboard-tg-vless | 5889 | yes | 4.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 1.29 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 3.07 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 125 |
| 204 | 30 |
| cn-block | 27 |
| speed | 25 |
