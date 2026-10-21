# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 03:53:33 |
| 运行耗时 | 639.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 95344 |
| 去重后节点 | 26608 |
| TCP 可达 | 3000 |
| 真实可用 | 378 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26608 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 44.4 |
| probe | 244.5 |
| real_test | 259.4 |
| generate | 82.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56804 |
| vmess | 16860 |
| shadowsocks | 11904 |
| trojan | 8117 |
| hysteria2 | 1212 |
| http | 171 |
| shadowsocksr | 164 |
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
| 80.02 | hysteria2 | 256.7 | 663.8 | 21.84 | 0.0 | 10.0 | 13.0 | 16.68 | Au1rxx-base64 | 129.213.91.185 |
| 78.95 | shadowsocks | 256.7 | 635.2 | 21.84 | 0.0 | 10.0 | 13.51 | 17.6 | mheidari-all | 156.146.38.170 |
| 78.67 | shadowsocks | 268.6 | 680.5 | 21.56 | 0.0 | 10.0 | 13.51 | 17.6 | mheidari-all | 37.19.198.243 |
| 77.94 | shadowsocks | 299.9 | 715.4 | 20.83 | 0.0 | 10.0 | 13.51 | 17.6 | mheidari-all | 37.19.198.160 |
| 77.2 | shadowsocks | 256.7 | 629.4 | 21.83 | 0.0 | 9.18 | 13.51 | 16.68 | Au1rxx-base64 | 156.146.38.168 |
| 76.98 | shadowsocks | 260.9 | 631.1 | 21.74 | 0.0 | 9.22 | 13.51 | 16.68 | Au1rxx-base64 | 156.146.38.167 |
| 76.8 | hysteria2 | 288.5 | 275.6 | 21.1 | 4.67 | 9.15 | 13.0 | 16.68 | Au1rxx-base64 | 45.32.10.7 |
| 75.69 | hysteria2 | 285.5 | 269.5 | 21.17 | 4.9 | 7.7 | 13.0 | 16.68 | Au1rxx-base64 | vp3.yysyy.online |
| 75.61 | hysteria2 | 279.7 | 600.6 | 21.3 | 0.0 | 8.79 | 13.0 | 16.68 | Au1rxx-base64 | 66.94.121.46 |
| 74.9 | vless | 256.7 | 638.4 | 21.84 | 0.0 | 10.0 | 10.88 | 16.68 | Au1rxx-base64 | uspanel.unixzone.us |
| 73.27 | vless | 261.9 | 679.2 | 21.71 | 0.0 | 10.0 | 10.88 | 16.68 | Au1rxx-base64 | youxuan.cf.090227.xyz |
| 73.2 | shadowsocks | 400.6 | 1006.4 | 18.51 | 0.0 | 10.0 | 13.51 | 16.68 | Au1rxx-base64 | 51.222.136.236 |
| 73.17 | vless | 266.5 | 705.8 | 21.61 | 0.0 | 10.0 | 10.88 | 16.68 | Au1rxx-base64 | nexusmods.com |
| 72.73 | vless | 324.0 | 609.2 | 20.28 | 0.0 | 10.0 | 10.88 | 16.68 | Au1rxx-base64 | 45.32.69.110 |
| 72.49 | vless | 295.8 | 564.4 | 20.93 | 0.0 | 10.0 | 10.88 | 17.6 | mheidari-all | 47.251.108.158 |
| 72.2 | vless | 328.2 | 637.2 | 20.18 | 0.0 | 9.24 | 10.88 | 16.68 | Au1rxx-base64 | 51.81.203.63 |
| 72.09 | shadowsocks | 298.1 | 581.7 | 20.88 | 0.0 | 10.0 | 13.51 | 16.68 | Au1rxx-base64 | 173.244.56.6 |
| 72.01 | shadowsocks | 278.9 | 693.6 | 21.32 | 0.0 | 10.0 | 13.51 | 16.68 | Au1rxx-base64 | 185.230.230.18 |
| 72.01 | hysteria2 | 387.4 | 721.9 | 18.81 | 0.0 | 9.94 | 13.0 | 17.6 | mheidari-all | 62.210.124.146 |
| 71.8 | shadowsocks | 310.6 | 655.4 | 20.59 | 0.0 | 9.18 | 13.51 | 16.68 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.952 | 0.898 | 254 | 1433 | prefer |
| zhangkai | 0.592 | 0.6 | 20 | 31 | observe |
| DeltaKronecker-all | 0.569 | 0.488 | 43 | 3519 | observe |
| ermaozi-get_subscribe | 0.557 | 0.538 | 39 | 516 | observe |
| mheidari-all | 0.536 | 0.456 | 193 | 23653 | observe |
| Surfboard-tg-mixed | 0.529 | 0.857 | 7 | 7115 | observe |
| SoliSpirit-all | 0.335 | 1.0 | 1 | 10016 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| Epodonios-all | 0.255 | None | 0 | 7598 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5552 | observe |
| barry-far-vless | 0.255 | None | 0 | 5764 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 60 |
| 204 | ProxyError | - | 29 |
| geo | ClientOSError | - | 29 |
| speed | ClientOSError | - | 23 |
| speed | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 8 |
| cn-block | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
