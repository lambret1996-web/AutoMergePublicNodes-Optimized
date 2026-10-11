# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-11 04:55:00 |
| 运行耗时 | 1163.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97524 |
| 去重后节点 | 27403 |
| TCP 可达 | 3000 |
| 真实可用 | 555 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27403 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.4 |
| tcp | 46.5 |
| probe | 414.0 |
| real_test | 615.4 |
| generate | 81.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56881 |
| vmess | 15826 |
| shadowsocks | 11877 |
| trojan | 10547 |
| hysteria2 | 1545 |
| http | 550 |
| shadowsocksr | 163 |
| socks | 75 |
| anytls | 37 |
| hysteria | 16 |
| tuic | 7 |

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
| 80.42 | hysteria2 | 274.8 | 713.1 | 21.42 | 0.0 | 10.0 | 11.88 | 18.62 | Au1rxx-base64 | 129.213.91.185 |
| 78.72 | shadowsocks | 249.9 | 626.5 | 21.99 | 0.0 | 10.0 | 12.11 | 18.62 | Au1rxx-base64 | 156.146.38.169 |
| 78.68 | shadowsocks | 251.8 | 632.3 | 21.95 | 0.0 | 10.0 | 12.11 | 18.62 | Au1rxx-base64 | 156.146.38.168 |
| 78.61 | hysteria2 | 270.5 | 263.6 | 21.52 | 5.11 | 9.25 | 11.88 | 18.62 | Au1rxx-base64 | vp3.yysyy.online |
| 77.81 | shadowsocks | 289.3 | 720.9 | 21.08 | 0.0 | 10.0 | 12.11 | 18.62 | Au1rxx-base64 | 156.146.38.167 |
| 77.39 | shadowsocks | 303.0 | 755.5 | 20.76 | 0.0 | 10.0 | 12.11 | 18.62 | Au1rxx-base64 | 37.19.198.244 |
| 77.31 | vless | 293.3 | 661.9 | 20.99 | 0.0 | 10.0 | 10.71 | 18.62 | Au1rxx-base64 | 172.245.253.16 |
| 77.12 | vless | 385.2 | 944.9 | 18.86 | 0.0 | 10.0 | 10.71 | 18.62 | Au1rxx-base64 | 185.95.231.156 |
| 76.88 | vless | 326.1 | 725.3 | 20.23 | 0.0 | 10.0 | 10.71 | 18.62 | Au1rxx-base64 | 159.89.87.21 |
| 76.85 | shadowsocks | 330.9 | 864.4 | 20.12 | 0.0 | 10.0 | 12.11 | 18.62 | Au1rxx-base64 | 156.146.38.170 |
| 76.46 | shadowsocks | 308.7 | 750.7 | 20.63 | 0.0 | 10.0 | 12.11 | 18.62 | Au1rxx-base64 | 37.19.198.160 |
| 76.41 | shadowsocks | 322.4 | 813.4 | 20.31 | 0.0 | 10.0 | 12.11 | 18.62 | Au1rxx-base64 | 37.19.198.236 |
| 76.38 | vless | 263.9 | 663.9 | 21.67 | 0.0 | 10.0 | 10.71 | 16.14 | mheidari-all | 195.211.98.43 |
| 76.33 | vless | 274.9 | 549.2 | 21.41 | 0.0 | 10.0 | 10.71 | 18.62 | Au1rxx-base64 | 47.251.108.158 |
| 76.19 | vless | 316.8 | 729.8 | 20.45 | 0.0 | 10.0 | 10.71 | 18.62 | Au1rxx-base64 | 137.184.218.169 |
| 76.06 | vless | 283.0 | 684.5 | 21.23 | 0.0 | 10.0 | 10.71 | 18.62 | Au1rxx-base64 | 69.48.201.136 |
| 75.91 | hysteria2 | 279.9 | 274.4 | 21.3 | 4.71 | 7.15 | 11.88 | 18.62 | Au1rxx-base64 | open.2ml.bid |
| 75.14 | shadowsocks | 315.7 | 785.5 | 20.47 | 0.0 | 10.0 | 12.11 | 18.62 | Au1rxx-base64 | 15.204.233.41 |
| 74.78 | vless | 347.9 | 771.2 | 19.72 | 0.0 | 10.0 | 10.71 | 18.62 | Au1rxx-base64 | 169.40.42.225 |
| 74.49 | vless | 330.6 | 627.5 | 20.12 | 0.0 | 10.0 | 10.71 | 18.62 | Au1rxx-base64 | 15.204.97.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | 0.918 | 390 | 1799 | prefer |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| Surfboard-tg-mixed | 0.624 | 0.818 | 11 | 7087 | observe |
| ermaozi-get_subscribe | 0.611 | 0.593 | 27 | 610 | observe |
| mheidari-all | 0.429 | 0.348 | 419 | 23694 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4347 | observe |
| DeltaKronecker-all | 0.272 | 0.286 | 7 | 5009 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7576 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9365 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5545 | observe |
| barry-far-vless | 0.255 | None | 0 | 5790 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 159 |
| speed | TimeoutError | - | 56 |
| geo | ClientOSError | - | 40 |
| speed | ClientOSError | - | 28 |
| cn-block | TimeoutError | - | 16 |
| 204 | ClientOSError | - | 9 |
| 204 | ProxyError | - | 9 |
| 204 | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
