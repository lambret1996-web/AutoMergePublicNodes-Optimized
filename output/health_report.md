# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 16:57:35 |
| 运行耗时 | 605.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96380 |
| 去重后节点 | 26688 |
| TCP 可达 | 3000 |
| 真实可用 | 333 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26688 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.5 |
| tcp | 45.9 |
| probe | 238.4 |
| real_test | 232.0 |
| generate | 80.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57047 |
| vmess | 17172 |
| shadowsocks | 12400 |
| trojan | 7906 |
| hysteria2 | 1347 |
| http | 239 |
| shadowsocksr | 166 |
| socks | 58 |
| anytls | 22 |
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
| 80.41 | shadowsocks | 245.7 | 633.0 | 22.09 | 0.0 | 9.1 | 14.38 | 18.84 | Au1rxx-base64 | 156.146.38.170 |
| 80.29 | shadowsocks | 242.1 | 606.4 | 22.17 | 0.0 | 10.0 | 14.38 | 17.74 | Surfboard-tg-mixed | 156.146.38.169 |
| 80.04 | hysteria2 | 295.5 | 650.7 | 20.94 | 0.0 | 9.15 | 14.0 | 18.84 | Au1rxx-base64 | 129.213.91.185 |
| 77.94 | vless | 248.2 | 549.8 | 22.03 | 0.0 | 10.0 | 8.53 | 18.84 | Au1rxx-base64 | 144.202.126.147 |
| 77.35 | vless | 245.7 | 546.2 | 22.09 | 0.0 | 9.15 | 8.53 | 18.84 | Au1rxx-base64 | 45.32.69.110 |
| 76.69 | trojan | 438.0 | 1163.2 | 17.64 | 0.0 | 9.11 | 14.1 | 18.84 | Au1rxx-base64 | 66.23.203.21 |
| 76.38 | vless | 288.8 | 653.8 | 21.09 | 0.0 | 9.15 | 8.53 | 18.84 | Au1rxx-base64 | 45.63.53.81 |
| 75.64 | shadowsocks | 237.3 | 594.1 | 22.28 | 0.0 | 9.14 | 14.38 | 18.84 | Au1rxx-base64 | 156.146.38.167 |
| 75.22 | shadowsocks | 303.3 | 302.6 | 20.76 | 3.65 | 9.07 | 14.38 | 18.84 | Au1rxx-base64 | 149.22.87.240 |
| 74.85 | shadowsocks | 329.8 | 742.8 | 20.14 | 0.0 | 9.11 | 14.38 | 18.84 | Au1rxx-base64 | 37.19.198.243 |
| 74.77 | shadowsocks | 342.3 | 714.0 | 19.85 | 0.0 | 10.0 | 14.38 | 18.84 | Au1rxx-base64 | 37.19.198.160 |
| 74.73 | shadowsocks | 372.2 | 935.7 | 19.16 | 0.0 | 9.12 | 14.38 | 18.84 | Au1rxx-base64 | 185.215.132.18 |
| 74.71 | shadowsocks | 326.3 | 748.8 | 20.22 | 0.0 | 10.0 | 14.38 | 18.84 | Au1rxx-base64 | 185.230.230.18 |
| 74.54 | shadowsocks | 299.6 | 600.0 | 20.84 | 0.0 | 9.1 | 14.38 | 18.84 | Au1rxx-base64 | 173.244.56.9 |
| 74.51 | shadowsocks | 313.1 | 655.1 | 20.53 | 0.0 | 9.07 | 14.38 | 18.84 | Au1rxx-base64 | 149.22.95.183 |
| 74.25 | shadowsocks | 335.3 | 769.8 | 20.02 | 0.0 | 9.07 | 14.38 | 18.84 | Au1rxx-base64 | 37.19.198.236 |
| 74.11 | shadowsocks | 352.2 | 874.7 | 19.63 | 0.0 | 9.13 | 14.38 | 18.84 | Au1rxx-base64 | 185.215.132.9 |
| 73.8 | vless | 240.6 | 531.2 | 22.21 | 0.0 | 10.0 | 8.53 | 18.84 | Au1rxx-base64 | 45.76.172.197 |
| 73.2 | shadowsocks | 317.0 | 723.9 | 20.44 | 0.0 | 9.15 | 14.38 | 18.84 | Au1rxx-base64 | 193.151.163.18 |
| 73.15 | vless | 287.6 | 574.0 | 21.12 | 0.0 | 8.5 | 8.53 | 18.84 | Au1rxx-base64 | tk1.high-speed-test-56424.me |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.958 | 0.894 | 47 | 24062 | prefer |
| Au1rxx-base64 | 0.892 | 0.834 | 241 | 1529 | prefer |
| Surfboard-tg-mixed | 0.709 | 0.632 | 114 | 7066 | prefer |
| DeltaKronecker-all | 0.373 | 0.6 | 5 | 3641 | observe |
| ermaozi | 0.364 | 0.333 | 42 | 573 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7538 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10202 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5426 | observe |
| barry-far-vless | 0.255 | None | 0 | 5601 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 28 |
| 204 | ProxyError | - | 25 |
| speed | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 12 |
| speed | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 7 |
| geo | ClientOSError | - | 6 |
| speed | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| geo | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
