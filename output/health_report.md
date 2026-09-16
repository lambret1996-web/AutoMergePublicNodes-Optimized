# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 06:37:18 |
| 运行耗时 | 879.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85286 |
| 去重后节点 | 22914 |
| TCP 可达 | 3000 |
| 真实可用 | 509 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22914 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.5 |
| tcp | 37.9 |
| probe | 300.7 |
| real_test | 445.1 |
| generate | 87.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52099 |
| vmess | 12926 |
| shadowsocks | 9500 |
| trojan | 8322 |
| hysteria2 | 1572 |
| http | 653 |
| shadowsocksr | 130 |
| socks | 68 |
| hysteria | 9 |
| tuic | 5 |
| anytls | 2 |

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
| 83.05 | hysteria2 | 287.2 | 809.8 | 21.13 | 0.0 | 10.0 | 13.42 | 19.5 | Au1rxx-base64 | 107.175.219.48 |
| 82.9 | hysteria2 | 196.9 | 510.6 | 23.22 | 0.0 | 10.0 | 13.42 | 17.26 | Surfboard-tg-mixed | 45.149.172.80 |
| 82.35 | shadowsocks | 233.7 | 555.9 | 22.37 | 0.0 | 10.0 | 14.48 | 19.5 | Au1rxx-base64 | 149.22.95.183 |
| 81.31 | hysteria2 | 222.2 | 559.8 | 22.63 | 0.0 | 10.0 | 13.42 | 17.26 | Surfboard-tg-mixed | 45.149.172.74 |
| 80.46 | shadowsocks | 196.8 | 473.8 | 23.22 | 0.0 | 10.0 | 14.48 | 19.5 | Au1rxx-base64 | 108.181.0.177 |
| 80.17 | vless | 206.4 | 519.7 | 23.0 | 0.0 | 10.0 | 7.67 | 19.5 | Au1rxx-base64 | 45.149.172.74 |
| 79.56 | vless | 232.9 | 498.3 | 22.39 | 0.0 | 10.0 | 7.67 | 19.5 | Au1rxx-base64 | 150.241.102.181 |
| 79.29 | shadowsocks | 247.4 | 648.2 | 22.05 | 0.0 | 10.0 | 14.48 | 17.26 | Surfboard-tg-mixed | 5.78.51.123 |
| 78.39 | vless | 256.5 | 525.0 | 21.84 | 0.0 | 10.0 | 7.67 | 19.5 | Au1rxx-base64 | 144.172.104.26 |
| 78.38 | vless | 197.1 | 520.2 | 23.21 | 0.0 | 10.0 | 7.67 | 19.5 | Au1rxx-base64 | 192.3.247.109 |
| 77.72 | trojan | 203.8 | 497.8 | 23.06 | 0.0 | 10.0 | 7.66 | 19.5 | Au1rxx-base64 | 100.42.228.109 |
| 77.56 | vless | 319.3 | 834.5 | 20.39 | 0.0 | 10.0 | 7.67 | 19.5 | Au1rxx-base64 | 15.204.97.216 |
| 77.49 | http | 208.2 | 504.2 | 22.96 | 0.0 | 10.0 | 11.59 | 15.94 | ermaozi | 138.199.35.197 |
| 77.49 | http | 208.3 | 492.9 | 22.96 | 0.0 | 10.0 | 11.59 | 15.94 | ermaozi | 138.199.35.210 |
| 77.47 | http | 209.0 | 503.2 | 22.94 | 0.0 | 10.0 | 11.59 | 15.94 | ermaozi | 138.199.35.216 |
| 77.46 | http | 209.4 | 501.0 | 22.93 | 0.0 | 10.0 | 11.59 | 15.94 | ermaozi | 138.199.35.214 |
| 77.37 | http | 213.2 | 502.2 | 22.84 | 0.0 | 10.0 | 11.59 | 15.94 | ermaozi | 138.199.35.206 |
| 77.29 | http | 216.7 | 510.9 | 22.76 | 0.0 | 10.0 | 11.59 | 15.94 | ermaozi | 138.199.35.201 |
| 76.82 | http | 193.7 | 484.8 | 23.29 | 0.0 | 10.0 | 11.59 | 15.94 | ermaozi | 138.199.35.220 |
| 76.52 | http | 207.0 | 499.1 | 22.99 | 0.0 | 10.0 | 11.59 | 15.94 | ermaozi | 138.199.35.205 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.913 | 0.849 | 284 | 1683 | prefer |
| mheidari-all | 0.768 | 0.692 | 91 | 16114 | prefer |
| ermaozi | 0.766 | 0.759 | 54 | 407 | prefer |
| Surfboard-tg-mixed | 0.686 | 0.607 | 178 | 7549 | observe |
| ermaozi-get_subscribe | 0.485 | 0.5 | 18 | 438 | observe |
| DeltaKronecker-all | 0.286 | 0.204 | 226 | 5932 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 178 | observe |
| Epodonios-all | 0.255 | None | 0 | 8003 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8866 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6134 | observe |
| barry-far-vless | 0.255 | None | 0 | 6340 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4206 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1683 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 135 |
| geo | ClientOSError | - | 59 |
| speed | TimeoutError | - | 36 |
| 204 | ProxyError | - | 31 |
| speed | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 18 |
| cn-block | ClientOSError | - | 13 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
