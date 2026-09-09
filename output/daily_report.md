# AutoNodes 每日报告

生成时间：2026-09-09 00:43:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 85335 |
| 去重后节点数 | 22916 |
| TCP 可达数 | 3000 |
| 真测通过数 | 576 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22916 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 78.6 |
| geo | 1.4 |
| probe | 308.8 |
| real_test | 483.3 |
| tcp | 37.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 33 | 21 | 12 | 63.6% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 187 | 173 | 14 | 92.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 54 | 47 | 7 | 87.0% |
| vless | 612 | 317 | 295 | 51.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 140 |
| geo:ClientOSError | 54 |
| speed:TimeoutError | 52 |
| speed:ClientOSError | 26 |
| 204:ProxyError | 16 |
| cn-block:TimeoutError | 15 |
| cn-block:ClientOSError | 10 |
| 204:TimeoutError | 7 |
| 204:ProxyConnectionError | 5 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4761 |
| ConnectionRefusedError | 887 |
| gaierror | 449 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | prefer | 267 | 0.906 | 1704 |
| Surfboard-tg-mixed | 0.875 | prefer | 213 | 0.798 | 7518 |
| ermaozi | 0.655 | observe | 34 | 0.647 | 409 |
| mheidari-all | 0.644 | observe | 179 | 0.564 | 16624 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| DeltaKronecker-all | 0.276 | observe | 207 | 0.193 | 6097 |
| Epodonios-all | 0.255 | observe | 0 | None | 7966 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8721 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6168 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.193 | 40 | 167 | 207 |
| mheidari-all | 0.564 | 101 | 78 | 179 |
| ermaozi | 0.647 | 22 | 12 | 34 |
| Surfboard-tg-mixed | 0.798 | 170 | 43 | 213 |
| Au1rxx-base64 | 0.906 | 242 | 25 | 267 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16624 | yes | 4.86 | 0 |
| SoliSpirit-all | 8721 | yes | 5.26 | 0 |
| Epodonios-all | 7966 | yes | 5.11 | 0 |
| Surfboard-tg-mixed | 7518 | yes | 4.37 | 0 |
| barry-far-vless | 6313 | yes | 0.52 | 0 |
| Surfboard-tg-vless | 6168 | yes | 4.12 | 0 |
| DeltaKronecker-all | 6097 | yes | 5.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 0.73 | 0 |
| mahdibland-V2RayAggregator | 4219 | yes | 3.14 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 0.83 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 195 |
| speed | 79 |
| 204 | 30 |
| cn-block | 26 |
