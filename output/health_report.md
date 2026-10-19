# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 03:54:37 |
| 运行耗时 | 739.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 97333 |
| 去重后节点 | 27718 |
| TCP 可达 | 3000 |
| 真实可用 | 473 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27718 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.5 |
| tcp | 48.8 |
| probe | 262.4 |
| real_test | 336.0 |
| generate | 82.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56873 |
| vmess | 16693 |
| shadowsocks | 11620 |
| trojan | 9521 |
| hysteria2 | 1576 |
| http | 761 |
| shadowsocksr | 167 |
| socks | 70 |
| anytls | 29 |
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
| 82.17 | hysteria2 | 227.7 | 566.0 | 22.51 | 0.0 | 10.0 | 12.5 | 18.16 | Au1rxx-base64 | 66.94.121.46 |
| 80.74 | vless | 217.7 | 474.6 | 22.74 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | 45.63.53.81 |
| 80.58 | vless | 253.3 | 578.8 | 21.91 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | 44.248.233.99 |
| 80.05 | vless | 204.4 | 516.5 | 23.05 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | 67.209.184.133 |
| 79.91 | vless | 296.6 | 713.2 | 20.91 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 79.83 | shadowsocks | 230.1 | 544.9 | 22.45 | 0.0 | 10.0 | 13.22 | 18.16 | Au1rxx-base64 | 173.244.56.6 |
| 79.31 | shadowsocks | 252.5 | 612.2 | 21.93 | 0.0 | 10.0 | 13.22 | 18.16 | Au1rxx-base64 | 149.22.95.183 |
| 77.6 | vless | 172.0 | 465.2 | 23.8 | 0.0 | 10.0 | 10.84 | 17.96 | mheidari-all | 47.251.108.158 |
| 77.49 | vless | 355.0 | 820.7 | 19.56 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | 154.40.55.185 |
| 77.4 | vless | 189.3 | 488.2 | 23.4 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | 131.143.180.87 |
| 77.02 | vless | 183.9 | 493.3 | 23.52 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | 136.175.179.94 |
| 76.81 | vless | 214.6 | 519.3 | 22.81 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | 195.123.240.65 |
| 76.32 | vless | 235.8 | 573.9 | 22.32 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | 15.204.97.214 |
| 75.92 | shadowsocks | 273.0 | 281.8 | 21.46 | 4.43 | 9.92 | 13.22 | 18.16 | Au1rxx-base64 | 149.22.87.241 |
| 75.82 | shadowsocks | 288.7 | 645.9 | 21.09 | 0.0 | 10.0 | 13.22 | 18.16 | Au1rxx-base64 | 156.146.38.167 |
| 75.56 | shadowsocks | 297.3 | 669.7 | 20.9 | 0.0 | 10.0 | 13.22 | 18.16 | Au1rxx-base64 | 156.146.38.168 |
| 75.55 | hysteria2 | 202.4 | 454.3 | 23.09 | 0.0 | 10.0 | 12.5 | 18.16 | Au1rxx-base64 | 179.255.104.98 |
| 75.25 | vless | 497.8 | 1353.4 | 16.25 | 0.0 | 10.0 | 10.84 | 18.16 | Au1rxx-base64 | 51.81.203.63 |
| 75.12 | shadowsocks | 293.8 | 657.8 | 20.98 | 0.0 | 10.0 | 13.22 | 18.16 | Au1rxx-base64 | 156.146.38.170 |
| 74.85 | hysteria2 | 281.2 | 175.6 | 21.27 | 8.42 | 9.92 | 12.5 | 18.16 | Au1rxx-base64 | 8.209.247.109 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.943 | 0.877 | 407 | 1698 | prefer |
| mheidari-all | 0.503 | 0.423 | 213 | 23518 | observe |
| Surfboard-tg-mixed | 0.446 | 0.625 | 8 | 7003 | observe |
| ermaozi | 0.374 | 0.34 | 50 | 696 | observe |
| DeltaKronecker-all | 0.361 | 0.4 | 10 | 4750 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| Epodonios-all | 0.255 | None | 0 | 7467 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9820 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5523 | observe |
| barry-far-vless | 0.255 | None | 0 | 5700 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1698 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 75 |
| speed | ClientOSError | - | 26 |
| geo | ClientOSError | - | 25 |
| 204 | ProxyError | - | 24 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyConnectionError | - | 16 |
| 204 | TimeoutError | - | 11 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
