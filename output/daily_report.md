# AutoNodes 每日报告

生成时间：2026-09-09 06:35:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 86181 |
| 去重后节点数 | 22674 |
| TCP 可达数 | 3000 |
| 真测通过数 | 550 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22674 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 76.8 |
| geo | 1.5 |
| probe | 299.7 |
| real_test | 309.6 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 69 | 48 | 21 | 69.6% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 170 | 161 | 9 | 94.7% |
| socks | 10 | 8 | 2 | 80.0% |
| trojan | 47 | 43 | 4 | 91.5% |
| vless | 395 | 276 | 119 | 69.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 30 |
| cn-block:ClientOSError | 28 |
| 204:ProxyError | 25 |
| speed:TimeoutError | 21 |
| geo:TimeoutError | 13 |
| 204:TimeoutError | 12 |
| cn-block:TimeoutError | 12 |
| speed:ClientOSError | 6 |
| geo:ProxyError | 6 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4866 |
| ConnectionRefusedError | 873 |
| gaierror | 398 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.904 | prefer | 279 | 0.839 | 1690 |
| Surfboard-tg-mixed | 0.875 | prefer | 183 | 0.798 | 7520 |
| mheidari-all | 0.824 | prefer | 131 | 0.748 | 16820 |
| ermaozi | 0.721 | prefer | 52 | 0.712 | 442 |
| ermaozi-get_subscribe | 0.664 | observe | 19 | 0.684 | 473 |
| DeltaKronecker-all | 0.621 | observe | 35 | 0.543 | 6097 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 180 |
| Epodonios-all | 0.255 | observe | 0 | None | 7969 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.543 | 19 | 16 | 35 |
| ermaozi-get_subscribe | 0.684 | 13 | 6 | 19 |
| ermaozi | 0.712 | 37 | 15 | 52 |
| mheidari-all | 0.748 | 98 | 33 | 131 |
| Surfboard-tg-mixed | 0.798 | 146 | 37 | 183 |
| Au1rxx-base64 | 0.839 | 234 | 45 | 279 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16820 | yes | 4.84 | 0 |
| SoliSpirit-all | 8998 | yes | 3.8 | 0 |
| Epodonios-all | 7969 | yes | 5.05 | 0 |
| Surfboard-tg-mixed | 7520 | yes | 4.1 | 0 |
| barry-far-vless | 6433 | yes | 2.2 | 0 |
| Surfboard-tg-vless | 6208 | yes | 4.38 | 0 |
| DeltaKronecker-all | 6097 | yes | 5.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 1.96 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 1.77 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 49 |
| cn-block | 41 |
| 204 | 38 |
| speed | 27 |
