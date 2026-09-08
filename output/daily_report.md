# AutoNodes 每日报告

生成时间：2026-09-08 12:28:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 90936 |
| 去重后节点数 | 25288 |
| TCP 可达数 | 3000 |
| 真测通过数 | 545 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25288 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 47.5 |
| geo | 1.5 |
| probe | 93.2 |
| real_test | 131.7 |
| tcp | 42.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 74 | 64 | 10 | 86.5% |
| hysteria2 | 25 | 19 | 6 | 76.0% |
| shadowsocks | 174 | 156 | 18 | 89.7% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 20 | 13 | 7 | 65.0% |
| vless | 429 | 284 | 145 | 66.2% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 44 |
| geo:ClientOSError | 43 |
| 204:TimeoutError | 33 |
| cn-block:TimeoutError | 27 |
| 204:ProxyConnectionError | 9 |
| speed:ClientOSError | 9 |
| speed:TimeoutError | 8 |
| 204:ClientOSError | 6 |
| 204:ProxyError | 4 |
| geo:TimeoutError | 4 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5242 |
| ConnectionRefusedError | 992 |
| gaierror | 500 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | prefer | 330 | 0.912 | 1727 |
| ermaozi | 0.863 | prefer | 56 | 0.857 | 450 |
| Surfboard-tg-mixed | 0.783 | prefer | 170 | 0.706 | 7431 |
| ermaozi-get_subscribe | 0.767 | prefer | 18 | 0.833 | 470 |
| mheidari-all | 0.452 | observe | 154 | 0.37 | 22334 |
| DeltaKronecker-all | 0.4 | observe | 4 | 0.75 | 6097 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 212 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| Epodonios-all | 0.255 | observe | 0 | None | 7885 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| mheidari-all | 0.37 | 57 | 97 | 154 |
| Surfboard-tg-mixed | 0.706 | 120 | 50 | 170 |
| DeltaKronecker-all | 0.75 | 3 | 1 | 4 |
| ermaozi-get_subscribe | 0.833 | 15 | 3 | 18 |
| ermaozi | 0.857 | 48 | 8 | 56 |
| Au1rxx-base64 | 0.912 | 301 | 29 | 330 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22334 | yes | 5.15 | 0 |
| SoliSpirit-all | 8435 | yes | 4.58 | 0 |
| Epodonios-all | 7885 | yes | 5.77 | 0 |
| Surfboard-tg-mixed | 7431 | yes | 4.26 | 0 |
| barry-far-vless | 6423 | yes | 2.94 | 0 |
| Surfboard-tg-vless | 6201 | yes | 4.48 | 0 |
| DeltaKronecker-all | 6097 | yes | 5.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 2.72 | 0 |
| mahdibland-V2RayAggregator | 4209 | yes | 3.28 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.04 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 73 |
| 204 | 52 |
| geo | 47 |
| speed | 17 |
