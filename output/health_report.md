# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-12 05:08:04 |
| 运行耗时 | 1041.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99740 |
| 去重后节点 | 27634 |
| TCP 可达 | 3000 |
| 真实可用 | 499 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27634 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.3 |
| tcp | 47.4 |
| probe | 352.5 |
| real_test | 541.2 |
| generate | 93.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58163 |
| vmess | 15776 |
| shadowsocks | 11937 |
| trojan | 11403 |
| hysteria2 | 1489 |
| http | 683 |
| shadowsocksr | 165 |
| socks | 69 |
| anytls | 31 |
| hysteria | 16 |
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
| 82.64 | vless | 245.6 | 650.5 | 22.09 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 169.40.42.225 |
| 82.55 | hysteria2 | 237.2 | 688.2 | 22.29 | 0.0 | 10.0 | 12.14 | 19.62 | Au1rxx-base64 | 129.213.91.185 |
| 82.12 | vless | 263.9 | 644.9 | 21.67 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 172.245.253.16 |
| 82.08 | vless | 270.0 | 715.9 | 21.53 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 169.40.42.104 |
| 81.9 | vless | 277.8 | 706.4 | 21.35 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 66.70.179.198 |
| 81.14 | vless | 310.5 | 720.8 | 20.59 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 169.40.42.74 |
| 80.83 | vless | 280.8 | 677.4 | 21.28 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 169.40.42.232 |
| 80.76 | vless | 326.7 | 884.9 | 20.21 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 137.184.218.169 |
| 80.75 | vless | 327.4 | 814.4 | 20.2 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 169.40.42.90 |
| 80.63 | shadowsocks | 249.0 | 697.1 | 22.02 | 0.0 | 10.0 | 12.99 | 19.62 | Au1rxx-base64 | 37.19.198.160 |
| 80.55 | shadowsocks | 252.1 | 708.1 | 21.94 | 0.0 | 10.0 | 12.99 | 19.62 | Au1rxx-base64 | 37.19.198.243 |
| 80.51 | shadowsocks | 253.7 | 708.4 | 21.9 | 0.0 | 10.0 | 12.99 | 19.62 | Au1rxx-base64 | 37.19.198.244 |
| 80.45 | shadowsocks | 256.7 | 720.7 | 21.84 | 0.0 | 10.0 | 12.99 | 19.62 | Au1rxx-base64 | 37.19.198.236 |
| 80.45 | vless | 340.3 | 821.7 | 19.9 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 169.40.42.16 |
| 80.38 | vless | 343.3 | 938.2 | 19.83 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 169.40.42.231 |
| 80.3 | shadowsocks | 241.4 | 664.1 | 22.19 | 0.0 | 10.0 | 12.99 | 19.62 | Au1rxx-base64 | 140.82.63.79 |
| 80.13 | vless | 354.2 | 978.6 | 19.58 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 185.95.231.156 |
| 79.22 | vless | 297.5 | 722.0 | 20.89 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 169.40.42.224 |
| 78.61 | vless | 333.6 | 832.0 | 20.06 | 0.0 | 10.0 | 10.93 | 19.62 | Au1rxx-base64 | 169.40.42.212 |
| 78.52 | shadowsocks | 318.4 | 915.7 | 20.41 | 0.0 | 10.0 | 12.99 | 19.62 | Au1rxx-base64 | 15.204.233.41 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | 0.901 | 393 | 1810 | prefer |
| DeltaKronecker-all | 0.736 | 0.661 | 59 | 5372 | prefer |
| ermaozi | 0.689 | 0.667 | 51 | 708 | observe |
| Surfboard-tg-mixed | 0.43 | 0.556 | 9 | 7200 | observe |
| SoliSpirit-all | 0.335 | 1.0 | 1 | 9918 | observe |
| mheidari-all | 0.315 | 0.233 | 279 | 23656 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| Epodonios-all | 0.255 | None | 0 | 7699 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5717 | observe |
| barry-far-vless | 0.255 | None | 0 | 5961 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4284 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1810 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 132 |
| speed | TimeoutError | - | 57 |
| geo | ClientOSError | - | 29 |
| 204 | ProxyError | - | 28 |
| speed | ClientOSError | - | 18 |
| 204 | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
