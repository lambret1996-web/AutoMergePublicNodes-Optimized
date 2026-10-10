# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-10 05:07:36 |
| 运行耗时 | 1080.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97894 |
| 去重后节点 | 27735 |
| TCP 可达 | 3000 |
| 真实可用 | 546 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27735 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.4 |
| tcp | 47.6 |
| probe | 350.9 |
| real_test | 604.9 |
| generate | 71.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57033 |
| vmess | 15713 |
| shadowsocks | 11920 |
| trojan | 10811 |
| hysteria2 | 1566 |
| http | 555 |
| shadowsocksr | 169 |
| socks | 70 |
| anytls | 28 |
| hysteria | 17 |
| tuic | 12 |

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
| 81.76 | hysteria2 | 279.1 | 714.0 | 21.32 | 0.0 | 10.0 | 13.04 | 18.9 | Au1rxx-base64 | 129.213.91.185 |
| 80.04 | shadowsocks | 246.4 | 643.2 | 22.08 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 156.146.38.169 |
| 79.99 | shadowsocks | 248.4 | 603.5 | 22.03 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 156.146.38.170 |
| 79.95 | shadowsocks | 250.2 | 642.3 | 21.99 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 156.146.38.167 |
| 79.95 | shadowsocks | 250.2 | 634.1 | 21.99 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 156.146.38.168 |
| 78.78 | vless | 292.8 | 696.0 | 21.0 | 0.0 | 10.0 | 9.98 | 18.9 | Au1rxx-base64 | 198.251.78.29 |
| 78.27 | shadowsocks | 304.6 | 753.0 | 20.73 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 37.19.198.243 |
| 78.12 | shadowsocks | 305.0 | 749.8 | 20.72 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 37.19.198.244 |
| 78.09 | vless | 239.8 | 601.2 | 22.23 | 0.0 | 10.0 | 9.98 | 17.88 | mheidari-all | 195.211.98.43 |
| 77.71 | hysteria2 | 324.4 | 645.2 | 20.27 | 0.0 | 10.0 | 13.04 | 18.9 | Au1rxx-base64 | 66.94.121.46 |
| 77.42 | shadowsocks | 303.8 | 687.0 | 20.75 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 140.82.63.79 |
| 77.27 | shadowsocks | 300.2 | 738.3 | 20.83 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 37.19.198.160 |
| 77.17 | shadowsocks | 305.8 | 752.4 | 20.7 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 37.19.198.236 |
| 76.54 | vless | 272.3 | 548.2 | 21.48 | 0.0 | 10.0 | 9.98 | 18.9 | Au1rxx-base64 | 47.251.108.158 |
| 76.18 | vless | 354.2 | 777.5 | 19.58 | 0.0 | 10.0 | 9.98 | 18.9 | Au1rxx-base64 | 66.70.179.198 |
| 75.83 | vless | 287.0 | 585.3 | 21.13 | 0.0 | 10.0 | 9.98 | 18.9 | Au1rxx-base64 | 107.173.237.146 |
| 75.3 | shadowsocks | 292.9 | 645.0 | 21.0 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 5.78.51.123 |
| 75.27 | shadowsocks | 300.8 | 800.2 | 20.81 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 66.23.204.218 |
| 75.2 | shadowsocks | 304.1 | 808.7 | 20.74 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 66.23.204.214 |
| 75.07 | shadowsocks | 396.1 | 1018.7 | 18.61 | 0.0 | 10.0 | 13.06 | 18.9 | Au1rxx-base64 | 15.204.247.206 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | 0.913 | 366 | 1786 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.875 | 0.803 | 71 | 7155 | prefer |
| ermaozi-get_subscribe | 0.626 | 0.607 | 28 | 653 | observe |
| mheidari-all | 0.382 | 0.301 | 382 | 23395 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4984 | observe |
| Epodonios-all | 0.255 | None | 0 | 7634 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9590 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5643 | observe |
| barry-far-vless | 0.255 | None | 0 | 5793 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4346 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1786 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 156 |
| speed | TimeoutError | - | 62 |
| geo | ClientOSError | - | 31 |
| 204 | ProxyError | - | 24 |
| speed | ClientOSError | - | 23 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
