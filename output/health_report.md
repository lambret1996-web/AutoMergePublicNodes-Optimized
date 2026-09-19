# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 06:31:01 |
| 运行耗时 | 641.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84235 |
| 去重后节点 | 23101 |
| TCP 可达 | 3000 |
| 真实可用 | 555 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23101 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 38.2 |
| probe | 275.8 |
| real_test | 291.7 |
| generate | 29.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50197 |
| vmess | 13752 |
| shadowsocks | 10022 |
| trojan | 8209 |
| hysteria2 | 1200 |
| http | 655 |
| shadowsocksr | 123 |
| socks | 64 |
| hysteria | 8 |
| anytls | 3 |
| tuic | 2 |

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
| 85.23 | hysteria2 | 229.8 | 545.3 | 22.46 | 0.0 | 10.0 | 14.29 | 19.48 | Au1rxx-base64 | 66.94.121.46 |
| 81.67 | shadowsocks | 241.0 | 612.1 | 22.2 | 0.0 | 10.0 | 13.99 | 19.48 | Au1rxx-base64 | 156.146.38.169 |
| 81.07 | shadowsocks | 266.9 | 695.4 | 21.6 | 0.0 | 10.0 | 13.99 | 19.48 | Au1rxx-base64 | 156.146.38.170 |
| 79.77 | shadowsocks | 323.2 | 854.4 | 20.3 | 0.0 | 10.0 | 13.99 | 19.48 | Au1rxx-base64 | 156.146.38.168 |
| 76.14 | shadowsocks | 280.5 | 733.7 | 21.29 | 0.0 | 10.0 | 13.99 | 14.86 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.98 | shadowsocks | 265.5 | 630.2 | 21.63 | 0.0 | 10.0 | 13.99 | 14.86 | Surfboard-tg-mixed | 23.150.248.20 |
| 75.8 | shadowsocks | 327.7 | 725.2 | 20.19 | 0.0 | 10.0 | 13.99 | 19.48 | Au1rxx-base64 | 37.19.198.236 |
| 75.51 | shadowsocks | 330.4 | 734.3 | 20.13 | 0.0 | 10.0 | 13.99 | 19.48 | Au1rxx-base64 | 37.19.198.244 |
| 75.49 | shadowsocks | 330.9 | 734.6 | 20.12 | 0.0 | 10.0 | 13.99 | 19.48 | Au1rxx-base64 | 37.19.198.160 |
| 75.49 | vless | 354.6 | 838.5 | 19.57 | 0.0 | 10.0 | 9.13 | 19.48 | Au1rxx-base64 | 15.204.97.216 |
| 75.39 | vless | 326.2 | 697.0 | 20.23 | 0.0 | 10.0 | 9.13 | 19.48 | Au1rxx-base64 | 198.251.78.29 |
| 75.38 | vless | 262.9 | 642.3 | 21.69 | 0.0 | 10.0 | 9.13 | 19.48 | Au1rxx-base64 | 38.180.242.205 |
| 73.72 | vless | 258.4 | 562.3 | 21.8 | 0.0 | 10.0 | 9.13 | 19.48 | Au1rxx-base64 | 103.175.79.4 |
| 73.62 | shadowsocks | 358.4 | 754.9 | 19.48 | 0.0 | 10.0 | 13.99 | 19.48 | Au1rxx-base64 | 108.181.57.93 |
| 73.61 | http | 248.5 | 546.4 | 22.03 | 0.0 | 10.0 | 9.71 | 16.42 | ermaozi | 138.199.35.212 |
| 73.58 | vless | 295.1 | 549.9 | 20.95 | 0.0 | 10.0 | 9.13 | 19.48 | Au1rxx-base64 | 198.200.42.129 |
| 73.41 | http | 255.0 | 565.0 | 21.88 | 0.0 | 10.0 | 9.71 | 16.42 | ermaozi | 138.199.35.206 |
| 73.37 | vless | 351.5 | 717.2 | 19.64 | 0.0 | 10.0 | 9.13 | 19.48 | Au1rxx-base64 | 195.123.235.177 |
| 73.29 | vless | 329.2 | 677.5 | 20.16 | 0.0 | 10.0 | 9.13 | 19.48 | Au1rxx-base64 | 31.58.50.200 |
| 73.15 | shadowsocks | 364.0 | 849.6 | 19.35 | 0.0 | 10.0 | 13.99 | 19.48 | Au1rxx-base64 | 198.98.53.130 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | 0.869 | 327 | 1702 | prefer |
| ermaozi | 0.764 | 0.76 | 50 | 358 | prefer |
| roosterkid-openproxylist-v2ray | 0.727 | 1.0 | 13 | 150 | prefer |
| Surfboard-tg-mixed | 0.685 | 0.606 | 241 | 7238 | observe |
| mheidari-all | 0.625 | 0.547 | 86 | 16187 | observe |
| DeltaKronecker-all | 0.4 | 0.315 | 73 | 6040 | observe |
| Au1rxx-clash | 0.379 | 1.0 | 2 | 1703 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| ermaozi-get_subscribe | 0.27 | 1.0 | 1 | 387 | observe |
| Epodonios-all | 0.255 | None | 0 | 7734 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8922 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5783 | observe |
| barry-far-vless | 0.255 | None | 0 | 6042 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 83 |
| speed | TimeoutError | - | 28 |
| geo | ClientOSError | - | 26 |
| speed | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 24 |
| 204 | ProxyError | - | 17 |
| 204 | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
