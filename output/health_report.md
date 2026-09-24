# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 11:42:13 |
| 运行耗时 | 566.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96309 |
| 去重后节点 | 26221 |
| TCP 可达 | 3000 |
| 真实可用 | 374 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26221 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.4 |
| tcp | 43.3 |
| probe | 268.5 |
| real_test | 174.1 |
| generate | 73.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58607 |
| vmess | 14917 |
| shadowsocks | 11189 |
| trojan | 9059 |
| hysteria2 | 1610 |
| http | 622 |
| shadowsocksr | 168 |
| socks | 86 |
| anytls | 24 |
| hysteria | 19 |
| tuic | 8 |

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
| 81.87 | shadowsocks | 239.1 | 608.4 | 22.24 | 0.0 | 10.0 | 14.47 | 19.16 | Au1rxx-base64 | 156.146.38.169 |
| 80.83 | shadowsocks | 245.9 | 636.0 | 22.08 | 0.0 | 9.12 | 14.47 | 19.16 | Au1rxx-base64 | 156.146.38.168 |
| 76.0 | shadowsocks | 264.6 | 624.7 | 21.65 | 0.0 | 10.0 | 14.47 | 19.16 | Au1rxx-base64 | 23.150.248.20 |
| 75.95 | shadowsocks | 241.8 | 621.9 | 22.18 | 0.0 | 9.14 | 14.47 | 19.16 | Au1rxx-base64 | 156.146.38.170 |
| 75.89 | shadowsocks | 245.7 | 636.6 | 22.09 | 0.0 | 9.17 | 14.47 | 19.16 | Au1rxx-base64 | 156.146.38.167 |
| 75.15 | shadowsocks | 307.7 | 308.6 | 20.66 | 3.43 | 9.09 | 14.47 | 19.16 | Au1rxx-base64 | 149.22.87.240 |
| 75.01 | shadowsocks | 335.9 | 763.0 | 20.0 | 0.0 | 9.13 | 14.47 | 19.16 | Au1rxx-base64 | 37.19.198.160 |
| 74.93 | shadowsocks | 342.8 | 782.3 | 19.84 | 0.0 | 9.16 | 14.47 | 19.16 | Au1rxx-base64 | 37.19.198.243 |
| 74.57 | shadowsocks | 346.9 | 785.6 | 19.75 | 0.0 | 9.11 | 14.47 | 19.16 | Au1rxx-base64 | 37.19.198.244 |
| 74.47 | shadowsocks | 359.8 | 839.4 | 19.45 | 0.0 | 9.09 | 14.47 | 19.16 | Au1rxx-base64 | 198.98.53.130 |
| 73.71 | shadowsocks | 373.1 | 865.2 | 19.14 | 0.0 | 9.05 | 14.47 | 19.16 | Au1rxx-base64 | 142.4.216.225 |
| 73.64 | shadowsocks | 410.6 | 949.6 | 18.27 | 0.0 | 9.07 | 14.47 | 19.16 | Au1rxx-base64 | 173.244.56.6 |
| 73.22 | shadowsocks | 359.2 | 328.9 | 19.46 | 2.67 | 9.04 | 14.47 | 19.16 | Au1rxx-base64 | 149.22.87.204 |
| 73.18 | vless | 277.1 | 634.2 | 21.36 | 0.0 | 9.18 | 5.57 | 19.16 | Au1rxx-base64 | 5.78.159.214 |
| 72.87 | shadowsocks | 316.9 | 724.7 | 20.44 | 0.0 | 10.0 | 14.47 | 15.48 | Surfboard-tg-mixed | 185.156.47.97 |
| 72.81 | shadowsocks | 311.6 | 700.2 | 20.57 | 0.0 | 10.0 | 14.47 | 15.48 | Surfboard-tg-mixed | 108.181.0.177 |
| 72.56 | http | 300.3 | 711.9 | 20.83 | 0.0 | 10.0 | 10.42 | 15.86 | ermaozi | 138.199.35.198 |
| 72.53 | shadowsocks | 371.5 | 796.4 | 19.18 | 0.0 | 9.03 | 14.47 | 19.16 | Au1rxx-base64 | 108.181.57.93 |
| 72.36 | http | 307.7 | 722.8 | 20.65 | 0.0 | 10.0 | 10.42 | 15.86 | ermaozi | 138.199.35.207 |
| 72.32 | http | 311.3 | 739.4 | 20.57 | 0.0 | 10.0 | 10.42 | 15.86 | ermaozi | 138.199.35.196 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | 0.881 | 218 | 1658 | prefer |
| Surfboard-tg-mixed | 0.765 | 0.688 | 109 | 7027 | prefer |
| ermaozi | 0.632 | 0.623 | 53 | 339 | observe |
| mheidari-all | 0.545 | 0.465 | 127 | 22399 | observe |
| DeltaKronecker-all | 0.507 | 0.75 | 8 | 5845 | observe |
| ermaozi-get_subscribe | 0.49 | 0.529 | 17 | 373 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5307 | observe |
| Epodonios-all | 0.255 | None | 0 | 7495 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8857 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5676 | observe |
| barry-far-vless | 0.255 | None | 0 | 5899 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4305 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 38 |
| cn-block | ClientOSError | - | 36 |
| 204 | TimeoutError | - | 27 |
| geo | TimeoutError | - | 16 |
| cn-block | TimeoutError | - | 15 |
| speed | TimeoutError | - | 15 |
| geo | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 2 |
| speed | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
