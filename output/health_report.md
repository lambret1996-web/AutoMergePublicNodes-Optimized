# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 03:45:36 |
| 运行耗时 | 881.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99131 |
| 去重后节点 | 27859 |
| TCP 可达 | 3000 |
| 真实可用 | 547 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27859 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.8 |
| tcp | 48.5 |
| probe | 323.1 |
| real_test | 418.2 |
| generate | 83.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58419 |
| vmess | 16740 |
| shadowsocks | 11812 |
| trojan | 9837 |
| hysteria2 | 1283 |
| http | 757 |
| shadowsocksr | 171 |
| socks | 65 |
| anytls | 24 |
| hysteria | 17 |
| tuic | 6 |

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
| 81.36 | hysteria2 | 229.4 | 238.6 | 22.47 | 6.05 | 9.91 | 12.5 | 17.28 | Au1rxx-base64 | 45.32.10.7 |
| 80.04 | vless | 195.1 | 502.3 | 23.26 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 45.32.69.110 |
| 79.96 | hysteria2 | 248.5 | 581.0 | 22.03 | 0.0 | 10.0 | 12.5 | 17.28 | Au1rxx-base64 | 66.94.121.46 |
| 79.44 | vless | 264.4 | 655.3 | 21.66 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 154.9.241.170 |
| 78.54 | vless | 212.3 | 528.7 | 22.86 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 154.40.55.185 |
| 78.29 | hysteria2 | 225.5 | 228.7 | 22.56 | 6.43 | 6.37 | 12.5 | 17.28 | Au1rxx-base64 | vp3.yysyy.online |
| 78.25 | vless | 296.8 | 712.4 | 20.91 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 147.45.60.160 |
| 77.88 | shadowsocks | 210.6 | 525.7 | 22.9 | 0.0 | 10.0 | 11.7 | 17.28 | Au1rxx-base64 | 173.244.56.9 |
| 77.6 | shadowsocks | 222.7 | 531.8 | 22.62 | 0.0 | 10.0 | 11.7 | 17.28 | Au1rxx-base64 | 173.244.56.6 |
| 77.55 | vless | 216.5 | 561.9 | 22.77 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 176.122.183.26 |
| 76.98 | vless | 240.9 | 640.2 | 22.2 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 45.63.53.81 |
| 76.73 | shadowsocks | 257.8 | 630.6 | 21.81 | 0.0 | 10.0 | 11.7 | 17.28 | Au1rxx-base64 | 156.146.38.167 |
| 76.43 | hysteria2 | 319.0 | 742.5 | 20.39 | 0.0 | 10.0 | 12.5 | 17.28 | Au1rxx-base64 | 129.213.91.185 |
| 76.13 | vless | 191.5 | 493.6 | 23.35 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 104.225.239.122 |
| 75.79 | vless | 287.8 | 600.4 | 21.12 | 0.0 | 9.98 | 10.5 | 17.28 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 75.75 | vless | 207.8 | 519.3 | 22.97 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 104.36.71.38 |
| 75.74 | vless | 208.1 | 492.1 | 22.96 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 47.251.25.74 |
| 75.73 | shadowsocks | 260.4 | 636.2 | 21.75 | 0.0 | 10.0 | 11.7 | 17.28 | Au1rxx-base64 | 156.146.38.170 |
| 75.44 | shadowsocks | 259.4 | 633.6 | 21.77 | 0.0 | 10.0 | 11.7 | 17.28 | Au1rxx-base64 | 156.146.38.168 |
| 75.18 | vless | 210.4 | 499.0 | 22.91 | 0.0 | 10.0 | 10.5 | 17.28 | Au1rxx-base64 | 47.77.196.79 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | 0.865 | 490 | 1798 | prefer |
| Surfboard-tg-mixed | 0.612 | 0.533 | 75 | 7181 | observe |
| ermaozi | 0.552 | 0.524 | 103 | 710 | observe |
| DeltaKronecker-all | 0.337 | 0.308 | 13 | 4999 | observe |
| mheidari-all | 0.266 | 0.181 | 138 | 23946 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Epodonios-all | 0.255 | None | 0 | 7667 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9901 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5616 | observe |
| barry-far-vless | 0.255 | None | 0 | 5884 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1798 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 105 |
| 204 | ProxyError | - | 51 |
| geo | ClientOSError | - | 28 |
| speed | TimeoutError | - | 23 |
| speed | ClientOSError | - | 23 |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 15 |
| cn-block | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
