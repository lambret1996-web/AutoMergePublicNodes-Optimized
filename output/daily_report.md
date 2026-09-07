# AutoNodes 每日报告

生成时间：2026-09-07 13:01:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94666 |
| 去重后节点数 | 24965 |
| TCP 可达数 | 3000 |
| 真测通过数 | 489 |
| verified 输出数 | 30 |
| global 输出数 | 30 |
| all 输出数 | 24965 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 53.2 |
| geo | 1.4 |
| probe | 86.5 |
| real_test | 128.3 |
| tcp | 41.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 22 | 2 | 91.7% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 63 | 61 | 2 | 96.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 8 | 7 | 1 | 87.5% |
| vless | 523 | 372 | 151 | 71.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 58 |
| geo:ClientOSError | 34 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 15 |
| speed:TimeoutError | 9 |
| speed:ClientOSError | 6 |
| geo:TimeoutError | 5 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| 204:ProxyConnectionError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5632 |
| ConnectionRefusedError | 1028 |
| gaierror | 393 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | prefer | 324 | 0.914 | 1788 |
| Surfboard-tg-mixed | 0.868 | prefer | 102 | 0.794 | 7247 |
| zhangkai | 0.852 | prefer | 24 | 0.875 | 144 |
| mheidari-all | 0.539 | observe | 192 | 0.458 | 21631 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 151 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4650 |
| Epodonios-all | 0.255 | observe | 0 | None | 7707 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8437 |

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
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.458 | 88 | 104 | 192 |
| Surfboard-tg-mixed | 0.794 | 81 | 21 | 102 |
| zhangkai | 0.875 | 21 | 3 | 24 |
| Au1rxx-base64 | 0.914 | 296 | 28 | 324 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21631 | yes | 5.75 | 0 |
| SoliSpirit-all | 8437 | yes | 2.45 | 0 |
| Epodonios-all | 7707 | yes | 3.31 | 0 |
| Surfboard-tg-mixed | 7247 | yes | 4.71 | 0 |
| DeltaKronecker-all | 6417 | yes | 3.53 | 0 |
| barry-far-vless | 6245 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 6030 | yes | 4.39 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 1.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 1.52 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 2.76 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 77 |
| geo | 39 |
| 204 | 27 |
| speed | 15 |
