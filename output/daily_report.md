# AutoNodes 每日报告

生成时间：2026-09-07 13:43:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94662 |
| 去重后节点数 | 24969 |
| TCP 可达数 | 3000 |
| 真测通过数 | 586 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24969 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 45.8 |
| geo | 1.4 |
| probe | 88.0 |
| real_test | 143.9 |
| tcp | 41.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 23 | 21 | 2 | 91.3% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 172 | 158 | 14 | 91.9% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 14 | 14 | 0 | 100.0% |
| vless | 516 | 362 | 154 | 70.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 45 |
| geo:ClientOSError | 36 |
| 204:TimeoutError | 36 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 11 |
| geo:TimeoutError | 8 |
| speed:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| 204:ProxyConnectionError | 2 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48510: bind: address already in use | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5223 |
| ConnectionRefusedError | 1027 |
| gaierror | 424 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | prefer | 323 | 0.926 | 1785 |
| zhangkai | 0.886 | prefer | 23 | 0.913 | 144 |
| Surfboard-tg-mixed | 0.86 | prefer | 171 | 0.784 | 7247 |
| mheidari-all | 0.618 | observe | 234 | 0.538 | 21631 |
| tg-oneclickvpnkeys | 0.364 | observe | 3 | 1.0 | 151 |
| 10ium-HighSpeed | 0.345 | observe | 2 | 1.0 | 839 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5750 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4650 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 6417 |
| Epodonios-all | 0.255 | observe | 0 | None | 7707 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.538 | 126 | 108 | 234 |
| Surfboard-tg-mixed | 0.784 | 134 | 37 | 171 |
| zhangkai | 0.913 | 21 | 2 | 23 |
| Au1rxx-base64 | 0.926 | 299 | 24 | 323 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 2 | 0 | 2 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21631 | yes | 4.75 | 0 |
| SoliSpirit-all | 8440 | yes | 5.01 | 0 |
| Epodonios-all | 7707 | yes | 3.0 | 0 |
| Surfboard-tg-mixed | 7247 | yes | 3.44 | 0 |
| DeltaKronecker-all | 6417 | yes | 4.99 | 0 |
| barry-far-vless | 6245 | yes | 2.59 | 0 |
| Surfboard-tg-vless | 6030 | yes | 4.17 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 2.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 1.84 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 0.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 64 |
| 204 | 51 |
| geo | 45 |
| speed | 10 |
| sing-box exited 1 | 1 |
