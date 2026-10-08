# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-08 18:45:38 |
| 运行耗时 | 664.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 88869 |
| 去重后节点 | 27205 |
| TCP 可达 | 3000 |
| 真实可用 | 363 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27205 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.6 |
| tcp | 46.3 |
| probe | 326.8 |
| real_test | 204.5 |
| generate | 78.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53241 |
| vmess | 12632 |
| shadowsocks | 11172 |
| trojan | 9681 |
| hysteria2 | 1416 |
| http | 412 |
| shadowsocksr | 169 |
| socks | 87 |
| anytls | 34 |
| hysteria | 16 |
| tuic | 9 |

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
| 83.01 | shadowsocks | 210.5 | 562.5 | 22.9 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 149.22.95.183 |
| 80.87 | hysteria2 | 227.7 | 226.2 | 22.51 | 6.52 | 10.0 | 13.42 | 19.66 | Au1rxx-base64 | 158.101.148.79 |
| 80.39 | shadowsocks | 215.9 | 585.9 | 22.78 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 5.78.51.123 |
| 79.75 | trojan | 360.3 | 878.1 | 19.44 | 0.0 | 10.0 | 13.15 | 19.66 | Au1rxx-base64 | 34.220.15.24 |
| 78.43 | shadowsocks | 264.6 | 553.6 | 21.65 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 108.181.0.177 |
| 78.15 | shadowsocks | 267.9 | 561.0 | 21.58 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 108.181.118.10 |
| 77.96 | vless | 215.8 | 552.9 | 22.78 | 0.0 | 10.0 | 5.52 | 19.66 | Au1rxx-base64 | 15.204.97.197 |
| 77.82 | vless | 221.8 | 571.2 | 22.64 | 0.0 | 10.0 | 5.52 | 19.66 | Au1rxx-base64 | 15.204.97.216 |
| 77.7 | hysteria2 | 351.6 | 772.9 | 19.64 | 0.0 | 10.0 | 13.42 | 19.66 | Au1rxx-base64 | 129.213.91.185 |
| 76.4 | trojan | 308.0 | 316.0 | 20.65 | 3.15 | 10.0 | 13.15 | 19.66 | Au1rxx-base64 | 45.32.52.173 |
| 76.16 | shadowsocks | 319.8 | 665.8 | 20.38 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 156.146.38.169 |
| 76.1 | shadowsocks | 323.7 | 625.6 | 20.28 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 173.244.56.9 |
| 75.51 | shadowsocks | 322.9 | 689.3 | 20.3 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 156.146.38.167 |
| 75.35 | shadowsocks | 323.0 | 675.8 | 20.3 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 156.146.38.168 |
| 75.33 | shadowsocks | 325.1 | 699.4 | 20.25 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 156.146.38.170 |
| 75.01 | vless | 281.0 | 464.2 | 21.27 | 0.0 | 10.0 | 5.52 | 19.66 | Au1rxx-base64 | 47.251.108.158 |
| 74.74 | trojan | 356.1 | 287.0 | 19.53 | 4.24 | 8.29 | 13.15 | 19.66 | Au1rxx-base64 | dynamic-imp.rooster465.autos |
| 73.49 | vless | 276.3 | 566.1 | 21.38 | 0.0 | 10.0 | 5.52 | 19.66 | Au1rxx-base64 | 195.123.240.65 |
| 73.25 | trojan | 356.1 | 364.9 | 19.53 | 1.32 | 10.0 | 13.15 | 19.66 | Au1rxx-base64 | 3.112.245.255 |
| 72.9 | shadowsocks | 394.6 | 807.1 | 18.64 | 0.0 | 10.0 | 14.45 | 19.66 | Au1rxx-base64 | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.96 | 1.0 | 20 | 144 | prefer |
| Au1rxx-base64 | 0.909 | 0.839 | 316 | 1813 | prefer |
| mheidari-all | 0.837 | 0.771 | 35 | 23205 | prefer |
| Surfboard-tg-mixed | 0.64 | 0.562 | 73 | 7187 | observe |
| DeltaKronecker-all | 0.37 | 0.312 | 16 | 5197 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5081 | observe |
| Epodonios-all | 0.255 | None | 0 | 7780 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5683 | observe |
| barry-far-vless | 0.255 | None | 0 | 6016 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4431 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1813 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 35 |
| cn-block | TimeoutError | - | 23 |
| 204 | ProxyError | - | 17 |
| speed | TimeoutError | - | 12 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| geo | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
