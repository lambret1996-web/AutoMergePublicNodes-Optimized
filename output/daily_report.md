# AutoNodes 每日报告

生成时间：2026-09-09 18:30:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83949 |
| 去重后节点数 | 21979 |
| TCP 可达数 | 3000 |
| 真测通过数 | 478 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21979 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 81.7 |
| geo | 1.4 |
| probe | 212.7 |
| real_test | 239.5 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 21 | 6 | 77.8% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 173 | 160 | 13 | 92.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 31 | 23 | 8 | 74.2% |
| vless | 352 | 251 | 101 | 71.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 40 |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 24 |
| 204:ProxyError | 13 |
| cn-block:ClientOSError | 6 |
| speed:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| 204:ProxyConnectionError | 4 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5065 |
| ConnectionRefusedError | 875 |
| gaierror | 376 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.973 | prefer | 290 | 0.914 | 1557 |
| ermaozi | 0.775 | prefer | 27 | 0.778 | 410 |
| Surfboard-tg-mixed | 0.767 | prefer | 145 | 0.69 | 7400 |
| DeltaKronecker-all | 0.705 | prefer | 30 | 0.633 | 5187 |
| mheidari-all | 0.699 | observe | 111 | 0.622 | 16196 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 190 |
| Au1rxx-clash | 0.317 | observe | 1 | 1.0 | 1558 |
| ermaozi-get_subscribe | 0.272 | observe | 1 | 1.0 | 418 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4795 |
| Epodonios-all | 0.255 | observe | 0 | None | 7880 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.622 | 69 | 42 | 111 |
| DeltaKronecker-all | 0.633 | 19 | 11 | 30 |
| Surfboard-tg-mixed | 0.69 | 100 | 45 | 145 |
| ermaozi | 0.778 | 21 | 6 | 27 |
| Au1rxx-base64 | 0.914 | 265 | 25 | 290 |
| Au1rxx-clash | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16196 | yes | 3.88 | 0 |
| SoliSpirit-all | 9272 | yes | 4.02 | 0 |
| Epodonios-all | 7880 | yes | 4.2 | 0 |
| Surfboard-tg-mixed | 7400 | yes | 2.93 | 0 |
| barry-far-vless | 6218 | yes | 2.34 | 0 |
| Surfboard-tg-vless | 5999 | yes | 1.41 | 0 |
| DeltaKronecker-all | 5187 | yes | 3.95 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 2.7 | 0 |
| mahdibland-V2RayAggregator | 4247 | yes | 1.19 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 44 |
| geo | 44 |
| cn-block | 32 |
| speed | 11 |
