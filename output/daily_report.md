# AutoNodes 每日报告

生成时间：2026-09-22 06:34:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/3 |
| 清理建议：优先/观察 | 1/103 |
| 原始节点数 | 91522 |
| 去重后节点数 | 24896 |
| TCP 可达数 | 3000 |
| 真测通过数 | 498 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24896 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 95.2 |
| geo | 1.5 |
| probe | 271.6 |
| real_test | 327.3 |
| tcp | 42.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 50 | 33 | 17 | 66.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 168 | 158 | 10 | 94.0% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 35 | 17 | 18 | 48.6% |
| vless | 543 | 268 | 275 | 49.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 71 |
| geo:TimeoutError | 70 |
| speed:ClientOSError | 36 |
| speed:TimeoutError | 35 |
| 204:TimeoutError | 31 |
| cn-block:ClientOSError | 25 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 20 |
| 204:ClientOSError | 9 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40530: bind: address already in use | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6182 |
| ConnectionRefusedError | 916 |
| OSError | 229 |
| gaierror | 179 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.912 | prefer | 302 | 0.848 | 1660 |
| ermaozi | 0.689 | observe | 44 | 0.682 | 369 |
| Surfboard-tg-mixed | 0.664 | observe | 241 | 0.585 | 7043 |
| mheidari-all | 0.476 | observe | 167 | 0.395 | 19848 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| Epodonios-all | 0.255 | observe | 0 | None | 7572 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9006 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5601 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.121 | 47 | 0.021 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | 10ium-ScrapeCategorize-Vless | 0.141 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ermaozi-get_subscribe | 0.235 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 8 | 8 |
| DeltaKronecker-all | 0.021 | 1 | 46 | 47 |
| mheidari-all | 0.395 | 66 | 101 | 167 |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| Surfboard-tg-mixed | 0.585 | 141 | 100 | 241 |
| ermaozi | 0.682 | 30 | 14 | 44 |
| Au1rxx-base64 | 0.848 | 256 | 46 | 302 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19848 | yes | 5.82 | 0 |
| SoliSpirit-all | 9006 | yes | 5.12 | 0 |
| Epodonios-all | 7572 | yes | 6.11 | 0 |
| Surfboard-tg-mixed | 7043 | yes | 4.69 | 0 |
| DeltaKronecker-all | 6181 | yes | 6.23 | 0 |
| barry-far-vless | 5890 | yes | 1.75 | 0 |
| Surfboard-tg-vless | 5601 | yes | 3.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 0.15 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 1.25 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 143 |
| speed | 71 |
| 204 | 60 |
| cn-block | 48 |
| sing-box exited 1 | 1 |
