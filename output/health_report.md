# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 06:27:57 |
| 运行耗时 | 336.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91344 |
| 去重后节点 | 25185 |
| TCP 可达 | 3000 |
| 真实可用 | 601 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25185 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 18.6 |
| geo | 1.5 |
| tcp | 41.7 |
| probe | 88.1 |
| real_test | 150.6 |
| generate | 35.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57229 |
| vmess | 12253 |
| shadowsocks | 10281 |
| trojan | 9063 |
| hysteria2 | 1793 |
| http | 503 |
| shadowsocksr | 127 |
| socks | 50 |
| anytls | 18 |
| hysteria | 16 |
| tuic | 11 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 80.57 | http | 310.1 | 487.7 | 20.6 | 0.0 | 10.0 | 14.48 | 19.86 | ermaozi | 138.199.35.198 |
| 79.05 | http | 296.5 | 475.4 | 20.91 | 0.0 | 10.0 | 14.48 | 19.86 | ermaozi | 138.199.35.216 |
| 78.55 | hysteria2 | 419.2 | 992.8 | 18.07 | 0.0 | 10.0 | 14.0 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 78.45 | vless | 275.5 | 579.8 | 21.4 | 0.0 | 10.0 | 10.18 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 78.1 | vless | 284.3 | 619.1 | 21.2 | 0.0 | 10.0 | 10.18 | 20.0 | Au1rxx-base64 | 38.244.20.160 |
| 77.97 | vless | 274.5 | 579.2 | 21.42 | 0.0 | 10.0 | 10.18 | 20.0 | Au1rxx-base64 | 23.94.227.94 |
| 77.92 | shadowsocks | 327.9 | 554.8 | 20.19 | 0.0 | 10.0 | 14.22 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 77.31 | vless | 352.9 | 835.3 | 19.61 | 0.0 | 10.0 | 10.18 | 20.0 | Au1rxx-base64 | 15.204.97.216 |
| 77.14 | vless | 293.2 | 573.1 | 20.99 | 0.0 | 10.0 | 10.18 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 76.65 | http | 242.3 | 533.3 | 22.17 | 0.0 | 10.0 | 14.48 | 19.86 | ermaozi | 138.199.35.219 |
| 76.36 | shadowsocks | 315.8 | 652.2 | 20.47 | 0.0 | 10.0 | 14.22 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 76.32 | shadowsocks | 332.7 | 670.8 | 20.08 | 0.0 | 10.0 | 14.22 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 76.31 | http | 245.7 | 551.5 | 22.09 | 0.0 | 10.0 | 14.48 | 19.86 | ermaozi | 138.199.35.214 |
| 76.07 | http | 256.6 | 537.0 | 21.84 | 0.0 | 10.0 | 14.48 | 19.86 | ermaozi | 138.199.35.210 |
| 75.12 | http | 317.9 | 481.7 | 20.42 | 0.0 | 10.0 | 14.48 | 19.86 | ermaozi | 138.199.35.196 |
| 75.04 | http | 309.0 | 486.6 | 20.62 | 0.0 | 10.0 | 14.48 | 19.86 | ermaozi | 138.199.35.205 |
| 74.9 | shadowsocks | 249.9 | 612.9 | 21.99 | 0.0 | 10.0 | 14.22 | 16.66 | Surfboard-tg-mixed | 156.146.38.170 |
| 74.88 | shadowsocks | 247.3 | 606.8 | 22.05 | 0.0 | 10.0 | 14.22 | 16.66 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.71 | http | 320.0 | 472.2 | 20.37 | 0.0 | 10.0 | 14.48 | 19.86 | ermaozi | 138.199.35.203 |
| 74.7 | shadowsocks | 244.0 | 611.1 | 22.13 | 0.0 | 10.0 | 14.22 | 16.66 | Surfboard-tg-mixed | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 1.0 | 53 | 450 | prefer |
| ermaozi-get_subscribe | 0.94 | 1.0 | 19 | 470 | prefer |
| Au1rxx-base64 | 0.932 | 0.861 | 352 | 1834 | prefer |
| Surfboard-tg-mixed | 0.818 | 0.741 | 185 | 7392 | prefer |
| tg-oneclickvpnkeys | 0.447 | 1.0 | 5 | 199 | observe |
| mheidari-all | 0.377 | 0.296 | 284 | 22287 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 6417 | observe |
| Epodonios-all | 0.255 | None | 0 | 7862 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8456 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6186 | observe |
| barry-far-vless | 0.255 | None | 0 | 6415 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4209 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1834 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 62 |
| cn-block | ClientOSError | - | 62 |
| speed | TimeoutError | - | 42 |
| geo | ClientOSError | - | 39 |
| speed | ClientOSError | - | 32 |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyError | - | 9 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
