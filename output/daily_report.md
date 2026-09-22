# AutoNodes 每日报告

生成时间：2026-09-22 12:31:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 91808 |
| 去重后节点数 | 25278 |
| TCP 可达数 | 3000 |
| 真测通过数 | 468 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25278 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 75.5 |
| geo | 1.5 |
| probe | 247.3 |
| real_test | 212.0 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 48 | 32 | 16 | 66.7% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 156 | 144 | 12 | 92.3% |
| socks | 7 | 2 | 5 | 28.6% |
| trojan | 10 | 6 | 4 | 60.0% |
| vless | 497 | 264 | 233 | 53.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 62 |
| cn-block:ClientOSError | 56 |
| speed:ClientOSError | 43 |
| 204:TimeoutError | 31 |
| 204:ProxyError | 24 |
| speed:TimeoutError | 14 |
| geo:TimeoutError | 14 |
| cn-block:TimeoutError | 14 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6229 |
| ConnectionRefusedError | 923 |
| OSError | 233 |
| gaierror | 199 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.951 | prefer | 278 | 0.888 | 1630 |
| ermaozi | 0.689 | observe | 44 | 0.682 | 369 |
| Surfboard-tg-mixed | 0.58 | observe | 154 | 0.5 | 7157 |
| mheidari-all | 0.513 | observe | 245 | 0.433 | 19835 |
| DeltaKronecker-all | 0.372 | observe | 9 | 0.444 | 6324 |
| ermaozi-get_subscribe | 0.309 | observe | 5 | 0.6 | 393 |
| xiaoji235-airport-v2ray-all | 0.259 | observe | 3 | 0.333 | 4242 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4915 |
| Epodonios-all | 0.255 | observe | 0 | None | 7611 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.433 | 106 | 139 | 245 |
| DeltaKronecker-all | 0.444 | 4 | 5 | 9 |
| Surfboard-tg-mixed | 0.5 | 77 | 77 | 154 |
| ermaozi-get_subscribe | 0.6 | 3 | 2 | 5 |
| ermaozi | 0.682 | 30 | 14 | 44 |
| Au1rxx-base64 | 0.888 | 247 | 31 | 278 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19835 | yes | 5.5 | 0 |
| SoliSpirit-all | 9025 | yes | 3.53 | 0 |
| Epodonios-all | 7611 | yes | 4.78 | 0 |
| Surfboard-tg-mixed | 7157 | yes | 4.44 | 0 |
| DeltaKronecker-all | 6324 | yes | 4.75 | 0 |
| barry-far-vless | 5817 | yes | 0.4 | 0 |
| Surfboard-tg-vless | 5792 | yes | 3.71 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 0.59 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 1.47 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 1.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 79 |
| cn-block | 73 |
| 204 | 61 |
| speed | 58 |
