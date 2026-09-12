# AutoNodes 每日报告

生成时间：2026-09-12 12:30:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83273 |
| 去重后节点数 | 22846 |
| TCP 可达数 | 3000 |
| 真测通过数 | 472 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22846 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 78.2 |
| geo | 1.5 |
| probe | 231.8 |
| real_test | 233.2 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 62 | 35 | 27 | 56.5% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 160 | 147 | 13 | 91.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 50 | 43 | 7 | 86.0% |
| vless | 328 | 224 | 104 | 68.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 46 |
| 204:ProxyError | 27 |
| speed:ClientOSError | 15 |
| speed:TimeoutError | 12 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 10 |
| 204:ProxyConnectionError | 9 |
| geo:TimeoutError | 8 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5301 |
| ConnectionRefusedError | 882 |
| gaierror | 426 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.917 | prefer | 289 | 0.855 | 1613 |
| DeltaKronecker-all | 0.853 | prefer | 42 | 0.786 | 5970 |
| Surfboard-tg-mixed | 0.792 | prefer | 144 | 0.715 | 7286 |
| mheidari-all | 0.696 | observe | 84 | 0.619 | 15747 |
| ermaozi | 0.633 | observe | 50 | 0.62 | 434 |
| ermaozi-get_subscribe | 0.327 | observe | 13 | 0.385 | 459 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7695 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8771 |

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
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.385 | 5 | 8 | 13 |
| mheidari-all | 0.619 | 52 | 32 | 84 |
| ermaozi | 0.62 | 31 | 19 | 50 |
| Surfboard-tg-mixed | 0.715 | 103 | 41 | 144 |
| DeltaKronecker-all | 0.786 | 33 | 9 | 42 |
| Au1rxx-base64 | 0.855 | 247 | 42 | 289 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15747 | yes | 5.81 | 0 |
| SoliSpirit-all | 8771 | yes | 4.45 | 0 |
| Epodonios-all | 7695 | yes | 3.44 | 0 |
| Surfboard-tg-mixed | 7286 | yes | 3.8 | 0 |
| barry-far-vless | 6084 | yes | 3.22 | 0 |
| DeltaKronecker-all | 5970 | yes | 4.82 | 0 |
| Surfboard-tg-vless | 5895 | yes | 4.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 3.43 | 0 |
| mahdibland-V2RayAggregator | 4207 | yes | 0.89 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.51 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 55 |
| 204 | 49 |
| speed | 27 |
| cn-block | 23 |
