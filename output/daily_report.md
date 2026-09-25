# AutoNodes 每日报告

生成时间：2026-09-25 17:11:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97420 |
| 去重后节点数 | 26478 |
| TCP 可达数 | 3000 |
| 真测通过数 | 330 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26478 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 15.3 |
| generate | 78.0 |
| geo | 1.5 |
| probe | 245.7 |
| real_test | 164.1 |
| tcp | 42.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 22 | 8 | 14 | 36.4% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 123 | 110 | 13 | 89.4% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 4 | 4 | 0 | 100.0% |
| vless | 271 | 191 | 80 | 70.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 30 |
| 204:ProxyError | 24 |
| cn-block:TimeoutError | 20 |
| cn-block:ClientOSError | 14 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| speed:ClientOSError | 4 |
| geo:TimeoutError | 3 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5523 |
| ConnectionRefusedError | 978 |
| gaierror | 443 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.917 | prefer | 250 | 0.852 | 1699 |
| Surfboard-tg-mixed | 0.772 | prefer | 37 | 0.703 | 7258 |
| mheidari-all | 0.723 | prefer | 127 | 0.646 | 22782 |
| ermaozi | 0.399 | observe | 16 | 0.438 | 304 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 176 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7757 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9237 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5857 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| ermaozi-get_subscribe | 0.0 | 0 | 4 | 4 |
| ermaozi | 0.438 | 7 | 9 | 16 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.646 | 82 | 45 | 127 |
| Surfboard-tg-mixed | 0.703 | 26 | 11 | 37 |
| Au1rxx-base64 | 0.852 | 213 | 37 | 250 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22782 | yes | 6.16 | 0 |
| SoliSpirit-all | 9237 | yes | 4.73 | 0 |
| Epodonios-all | 7757 | yes | 3.13 | 0 |
| Surfboard-tg-mixed | 7258 | yes | 4.45 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.25 | 0 |
| barry-far-vless | 6083 | yes | 3.38 | 0 |
| Surfboard-tg-vless | 5857 | yes | 3.91 | 0 |
| DeltaKronecker-all | 5452 | yes | 6.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 2.91 | 0 |
| mahdibland-V2RayAggregator | 4324 | yes | 3.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 60 |
| cn-block | 38 |
| speed | 11 |
| geo | 3 |
