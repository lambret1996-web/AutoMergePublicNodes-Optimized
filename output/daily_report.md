# AutoNodes 每日报告

生成时间：2026-09-07 13:12:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 94669 |
| 去重后节点数 | 24972 |
| TCP 可达数 | 1000 |
| 真测通过数 | 396 |
| verified 输出数 | 30 |
| global 输出数 | 30 |
| all 输出数 | 24972 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 28.4 |
| geo | 1.4 |
| probe | 35.8 |
| real_test | 108.3 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 24 | 24 | 0 | 100.0% |
| shadowsocks | 122 | 111 | 11 | 91.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 18 | 10 | 8 | 55.6% |
| vless | 265 | 221 | 44 | 83.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 14 |
| cn-block:ClientOSError | 11 |
| cn-block:TimeoutError | 10 |
| geo:ClientOSError | 10 |
| geo:TimeoutError | 6 |
| speed:ClientOSError | 4 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5997 |
| ConnectionRefusedError | 1007 |
| gaierror | 360 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | prefer | 327 | 0.908 | 1788 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.747 | prefer | 91 | 0.67 | 7247 |
| mheidari-all | 0.734 | prefer | 14 | 0.857 | 21631 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 151 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4650 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 6417 |
| Epodonios-all | 0.255 | observe | 0 | None | 7707 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.67 | 61 | 30 | 91 |
| mheidari-all | 0.857 | 12 | 2 | 14 |
| Au1rxx-base64 | 0.908 | 297 | 30 | 327 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21631 | yes | 3.51 | 0 |
| SoliSpirit-all | 8440 | yes | 3.17 | 0 |
| Epodonios-all | 7707 | yes | 1.39 | 0 |
| Surfboard-tg-mixed | 7247 | yes | 0.22 | 0 |
| DeltaKronecker-all | 6417 | yes | 3.91 | 0 |
| barry-far-vless | 6245 | yes | 2.13 | 0 |
| Surfboard-tg-vless | 6030 | yes | 3.92 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 1.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 2.35 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 1.21 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| output_guard_preserved | output shrink guard preserved previous files |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 22 |
| 204 | 20 |
| geo | 16 |
| speed | 6 |
