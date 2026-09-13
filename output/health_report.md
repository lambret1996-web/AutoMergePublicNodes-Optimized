# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 12:30:28 |
| 运行耗时 | 591.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 94187 |
| 去重后节点 | 25223 |
| TCP 可达 | 3000 |
| 真实可用 | 433 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25223 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.4 |
| tcp | 41.7 |
| probe | 228.8 |
| real_test | 216.7 |
| generate | 95.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57879 |
| vmess | 13472 |
| shadowsocks | 10874 |
| trojan | 8891 |
| hysteria2 | 2202 |
| http | 640 |
| shadowsocksr | 129 |
| socks | 60 |
| hysteria | 15 |
| anytls | 13 |
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
| 80.69 | hysteria2 | 236.6 | 637.8 | 22.3 | 0.0 | 10.0 | 13.85 | 15.64 | mheidari-all | 159.223.157.129 |
| 79.37 | vless | 230.4 | 603.1 | 22.44 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 195.123.235.177 |
| 79.31 | vless | 233.3 | 655.9 | 22.38 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 47.253.226.114 |
| 79.25 | vless | 235.6 | 644.5 | 22.32 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 47.89.186.170 |
| 78.93 | vless | 249.8 | 654.3 | 22.0 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 169.40.42.202 |
| 78.59 | vless | 264.1 | 686.3 | 21.66 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 169.40.42.163 |
| 78.45 | vless | 270.4 | 655.6 | 21.52 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 169.40.42.173 |
| 78.16 | vless | 282.8 | 635.2 | 21.23 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 169.40.42.90 |
| 78.1 | shadowsocks | 230.7 | 634.8 | 22.44 | 0.0 | 10.0 | 14.02 | 15.64 | mheidari-all | 37.19.198.236 |
| 78.09 | vless | 285.8 | 695.9 | 21.16 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 169.40.42.225 |
| 78.0 | shadowsocks | 235.1 | 648.2 | 22.34 | 0.0 | 10.0 | 14.02 | 15.64 | mheidari-all | 37.19.198.160 |
| 77.98 | shadowsocks | 235.9 | 645.3 | 22.32 | 0.0 | 10.0 | 14.02 | 15.64 | mheidari-all | 37.19.198.243 |
| 77.76 | shadowsocks | 331.5 | 952.5 | 20.1 | 0.0 | 10.0 | 14.02 | 18.14 | Au1rxx-base64 | 15.204.246.132 |
| 77.74 | vless | 300.9 | 827.2 | 20.81 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 137.184.218.169 |
| 77.59 | shadowsocks | 339.2 | 961.6 | 19.93 | 0.0 | 10.0 | 14.02 | 18.14 | Au1rxx-base64 | 15.204.247.206 |
| 77.17 | vless | 325.7 | 830.3 | 20.24 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 2.24.124.64 |
| 76.86 | vless | 338.8 | 869.2 | 19.93 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 169.40.42.15 |
| 76.75 | vless | 343.8 | 929.8 | 19.82 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 185.95.231.156 |
| 76.69 | vless | 346.4 | 926.1 | 19.76 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 169.40.42.231 |
| 76.6 | vless | 283.5 | 634.8 | 21.21 | 0.0 | 10.0 | 8.79 | 18.14 | Au1rxx-base64 | 169.40.42.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.948 | 0.876 | 89 | 7439 | prefer |
| Au1rxx-base64 | 0.887 | 0.824 | 278 | 1633 | prefer |
| ermaozi | 0.638 | 0.63 | 27 | 436 | observe |
| mheidari-all | 0.566 | 0.486 | 214 | 20485 | observe |
| ermaozi-get_subscribe | 0.328 | 0.385 | 13 | 464 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7887 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8929 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6075 | observe |
| barry-far-vless | 0.255 | None | 0 | 6291 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4221 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1633 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 58 |
| cn-block | ClientOSError | - | 39 |
| speed | ClientOSError | - | 26 |
| 204 | ProxyError | - | 23 |
| cn-block | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 11 |
| geo | TimeoutError | - | 8 |
| speed | TimeoutError | - | 6 |
| geo | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
