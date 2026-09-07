# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 13:01:11 |
| 运行耗时 | 317.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94666 |
| 去重后节点 | 24965 |
| TCP 可达 | 3000 |
| 真实可用 | 489 |
| Verified 输出 | 30 |
| Global 输出 | 30 |
| All 输出 | 24965 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 41.4 |
| probe | 86.5 |
| real_test | 128.3 |
| generate | 53.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59122 |
| vmess | 12777 |
| shadowsocks | 11096 |
| trojan | 9199 |
| hysteria2 | 2086 |
| http | 138 |
| shadowsocksr | 130 |
| socks | 61 |
| anytls | 22 |
| hysteria | 21 |
| tuic | 14 |

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
| 85.78 | vless | 205.3 | 523.4 | 23.03 | 0.0 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 172.233.139.46 |
| 85.7 | vless | 208.4 | 487.2 | 22.95 | 0.0 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 172.235.43.210 |
| 85.54 | vless | 215.5 | 505.7 | 22.79 | 0.0 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 172.235.38.85 |
| 85.37 | vless | 222.8 | 563.9 | 22.62 | 0.0 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 23.94.227.94 |
| 83.89 | hysteria2 | 211.8 | 532.0 | 22.87 | 0.0 | 10.0 | 13.24 | 18.78 | Au1rxx-base64 | 66.94.121.46 |
| 83.69 | vless | 208.9 | 534.5 | 22.94 | 0.0 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 38.244.20.160 |
| 81.65 | http | 272.9 | 683.1 | 21.46 | 0.0 | 10.0 | 13.85 | 19.34 | zhangkai | 138.199.35.216 |
| 79.38 | vless | 236.0 | 484.6 | 22.31 | 0.0 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 162.159.39.218 |
| 79.36 | vless | 286.7 | 374.1 | 21.14 | 0.97 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 172.64.229.170 |
| 78.67 | vless | 318.0 | 623.3 | 20.42 | 0.0 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 172.64.53.55 |
| 78.37 | http | 284.9 | 675.5 | 21.18 | 0.0 | 10.0 | 13.85 | 19.34 | zhangkai | 138.199.35.198 |
| 77.85 | vless | 389.5 | 291.6 | 18.76 | 4.06 | 9.92 | 13.97 | 18.78 | Au1rxx-base64 | 52.194.245.53 |
| 77.83 | vless | 276.9 | 673.1 | 21.37 | 0.0 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 31.58.50.200 |
| 77.8 | vless | 226.0 | 493.5 | 22.55 | 0.0 | 10.0 | 13.97 | 18.78 | Au1rxx-base64 | 162.159.38.127 |
| 77.55 | vless | 380.4 | 307.6 | 18.97 | 3.47 | 9.92 | 13.97 | 18.78 | Au1rxx-base64 | 3.113.9.16 |
| 77.44 | vless | 351.4 | 328.0 | 19.64 | 2.7 | 9.9 | 13.97 | 18.78 | Au1rxx-base64 | 3.114.220.22 |
| 77.31 | vless | 338.1 | 339.8 | 19.95 | 2.26 | 9.92 | 13.97 | 18.78 | Au1rxx-base64 | 13.231.156.101 |
| 77.28 | vless | 341.4 | 339.5 | 19.88 | 2.27 | 9.9 | 13.97 | 18.78 | Au1rxx-base64 | 13.230.140.251 |
| 77.22 | vless | 378.3 | 317.7 | 19.02 | 3.09 | 9.93 | 13.97 | 18.78 | Au1rxx-base64 | 3.112.131.211 |
| 77.16 | vless | 349.2 | 325.6 | 19.7 | 2.79 | 9.93 | 13.97 | 18.78 | Au1rxx-base64 | 18.183.215.124 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | 0.914 | 324 | 1788 | prefer |
| Surfboard-tg-mixed | 0.868 | 0.794 | 102 | 7247 | prefer |
| zhangkai | 0.852 | 0.875 | 24 | 144 | prefer |
| mheidari-all | 0.539 | 0.458 | 192 | 21631 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 151 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| Epodonios-all | 0.255 | None | 0 | 7707 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8437 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6030 | observe |
| barry-far-vless | 0.255 | None | 0 | 6245 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5750 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1788 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 58 |
| geo | ClientOSError | - | 34 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 15 |
| speed | TimeoutError | - | 9 |
| speed | ClientOSError | - | 6 |
| geo | TimeoutError | - | 5 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 30 | 30 | - |
| global | False | 30 | 30 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
