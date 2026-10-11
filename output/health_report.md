# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-11 17:42:23 |
| 运行耗时 | 849.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99904 |
| 去重后节点 | 27587 |
| TCP 可达 | 3000 |
| 真实可用 | 479 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27587 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.5 |
| tcp | 47.2 |
| probe | 344.9 |
| real_test | 362.8 |
| generate | 87.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58791 |
| vmess | 15841 |
| shadowsocks | 11858 |
| trojan | 10966 |
| hysteria2 | 1517 |
| http | 634 |
| shadowsocksr | 166 |
| socks | 75 |
| anytls | 30 |
| hysteria | 16 |
| tuic | 10 |

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
| 85.09 | hysteria2 | 239.5 | 234.5 | 22.23 | 6.21 | 9.82 | 13.97 | 19.76 | Au1rxx-base64 | 158.101.148.79 |
| 81.04 | shadowsocks | 257.6 | 627.6 | 21.82 | 0.0 | 10.0 | 13.46 | 19.76 | Au1rxx-base64 | 156.146.38.168 |
| 80.75 | shadowsocks | 259.4 | 624.3 | 21.77 | 0.0 | 10.0 | 13.46 | 19.76 | Au1rxx-base64 | 156.146.38.170 |
| 80.66 | hysteria2 | 320.0 | 737.6 | 20.37 | 0.0 | 10.0 | 13.97 | 19.76 | Au1rxx-base64 | 129.213.91.185 |
| 80.65 | shadowsocks | 262.3 | 640.0 | 21.71 | 0.0 | 10.0 | 13.46 | 19.76 | Au1rxx-base64 | 156.146.38.167 |
| 79.91 | shadowsocks | 306.3 | 766.4 | 20.69 | 0.0 | 10.0 | 13.46 | 19.76 | Au1rxx-base64 | 156.146.38.169 |
| 79.43 | vless | 208.5 | 497.4 | 22.95 | 0.0 | 10.0 | 6.72 | 19.76 | Au1rxx-base64 | 137.175.82.40 |
| 79.3 | vless | 214.1 | 502.2 | 22.82 | 0.0 | 10.0 | 6.72 | 19.76 | Au1rxx-base64 | 47.251.108.158 |
| 78.93 | hysteria2 | 245.7 | 269.1 | 22.09 | 4.91 | 5.02 | 13.97 | 19.76 | Au1rxx-base64 | open.2ml.bid |
| 78.82 | vless | 234.8 | 630.3 | 22.34 | 0.0 | 10.0 | 6.72 | 19.76 | Au1rxx-base64 | 107.173.237.146 |
| 78.79 | shadowsocks | 301.7 | 736.9 | 20.79 | 0.0 | 10.0 | 13.46 | 19.76 | Au1rxx-base64 | 5.78.51.123 |
| 78.73 | vless | 195.7 | 507.0 | 23.25 | 0.0 | 10.0 | 6.72 | 19.76 | Au1rxx-base64 | 144.202.126.147 |
| 78.17 | vless | 262.9 | 668.0 | 21.69 | 0.0 | 10.0 | 6.72 | 19.76 | Au1rxx-base64 | 154.12.38.202 |
| 78.13 | shadowsocks | 261.0 | 600.1 | 21.74 | 0.0 | 10.0 | 13.46 | 19.76 | Au1rxx-base64 | 173.244.56.6 |
| 77.53 | shadowsocks | 279.3 | 285.0 | 21.31 | 4.31 | 9.9 | 13.46 | 19.76 | Au1rxx-base64 | 149.22.87.241 |
| 77.3 | shadowsocks | 181.3 | 487.6 | 23.58 | 0.0 | 10.0 | 13.46 | 19.76 | Au1rxx-base64 | 64.110.25.2 |
| 76.9 | vless | 274.5 | 693.6 | 21.42 | 0.0 | 10.0 | 6.72 | 19.76 | Au1rxx-base64 | 154.12.38.159 |
| 76.19 | vless | 267.0 | 587.9 | 21.6 | 0.0 | 10.0 | 6.72 | 19.76 | Au1rxx-base64 | 15.204.97.197 |
| 76.01 | vless | 271.9 | 602.2 | 21.48 | 0.0 | 10.0 | 6.72 | 19.76 | Au1rxx-base64 | 15.204.97.216 |
| 74.84 | vless | 190.8 | 495.7 | 23.36 | 0.0 | 10.0 | 6.72 | 19.76 | Au1rxx-base64 | 104.207.152.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | 0.909 | 361 | 1860 | prefer |
| mheidari-all | 0.849 | 0.78 | 50 | 23983 | prefer |
| DeltaKronecker-all | 0.78 | 0.714 | 28 | 5372 | prefer |
| Surfboard-tg-mixed | 0.726 | 0.648 | 125 | 7223 | prefer |
| ermaozi | 0.493 | 0.5 | 18 | 635 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5099 | observe |
| Epodonios-all | 0.255 | None | 0 | 7642 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9946 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5723 | observe |
| barry-far-vless | 0.255 | None | 0 | 5910 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1860 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 28 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyError | - | 14 |
| geo | ClientOSError | - | 14 |
| speed | TimeoutError | - | 13 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
