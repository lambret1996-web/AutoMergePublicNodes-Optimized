# AutoNodes 每日报告

生成时间：2026-09-17 12:33:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 86898 |
| 去重后节点数 | 24190 |
| TCP 可达数 | 3000 |
| 真测通过数 | 425 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24190 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 81.3 |
| geo | 1.4 |
| probe | 277.2 |
| real_test | 243.7 |
| tcp | 40.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 75 | 44 | 31 | 58.7% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 162 | 142 | 20 | 87.7% |
| socks | 5 | 5 | 0 | 100.0% |
| trojan | 8 | 6 | 2 | 75.0% |
| vless | 309 | 205 | 104 | 66.3% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 35 |
| geo:ClientOSError | 30 |
| 204:TimeoutError | 22 |
| speed:TimeoutError | 18 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 14 |
| geo:TimeoutError | 8 |
| 204:ProxyConnectionError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5053 |
| ConnectionRefusedError | 915 |
| gaierror | 402 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.905 | prefer | 55 | 0.836 | 16008 |
| Au1rxx-base64 | 0.899 | prefer | 266 | 0.835 | 1663 |
| ermaozi | 0.73 | prefer | 54 | 0.722 | 396 |
| Surfboard-tg-mixed | 0.693 | observe | 135 | 0.615 | 7408 |
| DeltaKronecker-all | 0.629 | observe | 49 | 0.551 | 5931 |
| ermaozi-get_subscribe | 0.337 | observe | 23 | 0.304 | 431 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 129 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5093 |
| Epodonios-all | 0.255 | observe | 0 | None | 7867 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.304 | 7 | 16 | 23 |
| DeltaKronecker-all | 0.551 | 27 | 22 | 49 |
| Surfboard-tg-mixed | 0.615 | 83 | 52 | 135 |
| ermaozi | 0.722 | 39 | 15 | 54 |
| Au1rxx-base64 | 0.835 | 222 | 44 | 266 |
| mheidari-all | 0.836 | 46 | 9 | 55 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16008 | yes | 4.8 | 0 |
| SoliSpirit-all | 8874 | yes | 3.77 | 0 |
| Epodonios-all | 7867 | yes | 5.03 | 0 |
| Surfboard-tg-mixed | 7408 | yes | 3.56 | 0 |
| barry-far-vless | 6149 | yes | 1.22 | 0 |
| DeltaKronecker-all | 5931 | yes | 5.43 | 0 |
| Surfboard-tg-vless | 5925 | yes | 4.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 1.69 | 0 |
| mahdibland-V2RayAggregator | 4179 | yes | 3.25 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 66 |
| geo | 38 |
| speed | 32 |
| cn-block | 22 |
