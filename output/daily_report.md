# AutoNodes 每日报告

生成时间：2026-09-14 06:36:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 84629 |
| 去重后节点数 | 22797 |
| TCP 可达数 | 3000 |
| 真测通过数 | 502 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22797 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 74.1 |
| geo | 1.4 |
| probe | 231.6 |
| real_test | 328.1 |
| tcp | 37.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 65 | 43 | 22 | 66.2% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 168 | 151 | 17 | 89.9% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 53 | 28 | 25 | 52.8% |
| vless | 409 | 257 | 152 | 62.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 61 |
| geo:ClientOSError | 31 |
| 204:ProxyError | 28 |
| speed:TimeoutError | 24 |
| speed:ClientOSError | 23 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 13 |
| 204:ProxyConnectionError | 11 |
| cn-block:ClientOSError | 9 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4574 |
| ConnectionRefusedError | 892 |
| gaierror | 472 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | prefer | 299 | 0.87 | 1681 |
| Surfboard-tg-mixed | 0.768 | prefer | 168 | 0.69 | 7444 |
| ermaozi | 0.696 | observe | 51 | 0.686 | 417 |
| mheidari-all | 0.633 | observe | 101 | 0.554 | 15963 |
| ermaozi-get_subscribe | 0.51 | observe | 15 | 0.6 | 444 |
| DeltaKronecker-all | 0.378 | observe | 82 | 0.293 | 5892 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Epodonios-all | 0.255 | observe | 0 | None | 7945 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8951 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.293 | 24 | 58 | 82 |
| roosterkid-openproxylist-v2ray | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.554 | 56 | 45 | 101 |
| ermaozi-get_subscribe | 0.6 | 9 | 6 | 15 |
| ermaozi | 0.686 | 35 | 16 | 51 |
| Surfboard-tg-mixed | 0.69 | 116 | 52 | 168 |
| Au1rxx-base64 | 0.87 | 260 | 39 | 299 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15963 | yes | 5.56 | 0 |
| SoliSpirit-all | 8951 | yes | 3.06 | 0 |
| Epodonios-all | 7945 | yes | 3.59 | 0 |
| Surfboard-tg-mixed | 7444 | yes | 4.18 | 0 |
| barry-far-vless | 6325 | yes | 1.39 | 0 |
| Surfboard-tg-vless | 6094 | yes | 4.39 | 0 |
| DeltaKronecker-all | 5892 | yes | 5.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 1.85 | 0 |
| mahdibland-V2RayAggregator | 4176 | yes | 3.27 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.52 | 0 |

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
| geo | 92 |
| 204 | 54 |
| speed | 48 |
| cn-block | 25 |
