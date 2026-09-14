# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 00:36:14 |
| 运行耗时 | 680.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 89696 |
| 去重后节点 | 25345 |
| TCP 可达 | 3000 |
| 真实可用 | 520 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25345 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.4 |
| tcp | 42.3 |
| probe | 244.6 |
| real_test | 310.7 |
| generate | 74.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54595 |
| vmess | 13428 |
| shadowsocks | 10567 |
| trojan | 8330 |
| hysteria2 | 1935 |
| http | 612 |
| shadowsocksr | 131 |
| socks | 59 |
| tuic | 17 |
| hysteria | 14 |
| anytls | 8 |

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
| 82.97 | hysteria2 | 240.8 | 642.9 | 22.2 | 0.0 | 10.0 | 13.85 | 18.02 | Au1rxx-base64 | 159.223.157.129 |
| 78.93 | shadowsocks | 272.9 | 744.6 | 21.46 | 0.0 | 10.0 | 13.45 | 18.02 | Au1rxx-base64 | 37.19.198.160 |
| 78.85 | vless | 246.3 | 688.6 | 22.08 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 47.253.226.114 |
| 78.83 | vless | 247.2 | 623.6 | 22.06 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 195.123.235.177 |
| 78.81 | vless | 248.0 | 651.3 | 22.04 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 169.40.42.133 |
| 78.64 | shadowsocks | 285.3 | 792.8 | 21.17 | 0.0 | 10.0 | 13.45 | 18.02 | Au1rxx-base64 | 37.19.198.236 |
| 78.34 | vless | 268.0 | 648.8 | 21.57 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 169.40.42.184 |
| 78.07 | vless | 280.0 | 739.4 | 21.3 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 169.40.42.89 |
| 78.01 | vless | 282.3 | 690.4 | 21.24 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 169.40.42.179 |
| 77.95 | hysteria2 | 291.9 | 578.7 | 21.02 | 0.0 | 10.0 | 13.85 | 18.02 | Au1rxx-base64 | 66.94.121.46 |
| 77.8 | shadowsocks | 300.0 | 822.9 | 20.83 | 0.0 | 10.0 | 13.45 | 18.02 | Au1rxx-base64 | 38.180.135.156 |
| 77.71 | vless | 295.4 | 794.0 | 20.94 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 169.40.42.229 |
| 77.61 | shadowsocks | 308.4 | 792.6 | 20.64 | 0.0 | 10.0 | 13.45 | 18.02 | Au1rxx-base64 | 51.222.12.127 |
| 77.35 | vless | 311.2 | 854.0 | 20.58 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 137.184.218.169 |
| 77.27 | vless | 314.6 | 703.1 | 20.5 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 169.40.42.225 |
| 76.77 | shadowsocks | 344.5 | 997.6 | 19.8 | 0.0 | 10.0 | 13.45 | 18.02 | Au1rxx-base64 | 15.204.247.206 |
| 76.68 | vless | 249.2 | 670.0 | 22.01 | 0.0 | 10.0 | 8.75 | 15.92 | Surfboard-tg-mixed | 47.89.186.170 |
| 76.68 | vless | 339.9 | 800.2 | 19.91 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 169.40.42.104 |
| 76.58 | shadowsocks | 288.2 | 806.0 | 21.11 | 0.0 | 10.0 | 13.45 | 18.02 | Au1rxx-base64 | 37.19.198.244 |
| 76.43 | vless | 253.3 | 665.5 | 21.91 | 0.0 | 10.0 | 8.75 | 18.02 | Au1rxx-base64 | 169.40.42.35 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.962 | 0.898 | 324 | 1660 | prefer |
| Surfboard-tg-mixed | 0.755 | 0.677 | 198 | 7507 | prefer |
| ermaozi | 0.637 | 0.629 | 35 | 382 | observe |
| mheidari-all | 0.457 | 0.375 | 112 | 15930 | observe |
| DeltaKronecker-all | 0.382 | 0.295 | 61 | 5892 | observe |
| xiaoji235-airport-v2ray-all | 0.366 | 0.275 | 40 | 5301 | observe |
| Epodonios-all | 0.255 | None | 0 | 7970 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8791 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6135 | observe |
| barry-far-vless | 0.255 | None | 0 | 6350 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1660 | observe |
| 10ium-ScrapeCategorize-Vless | 0.24 | 0.25 | 4 | 4839 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 61 |
| speed | TimeoutError | - | 50 |
| geo | ClientOSError | - | 40 |
| speed | ClientOSError | - | 32 |
| cn-block | ClientOSError | - | 26 |
| 204 | ProxyError | - | 22 |
| cn-block | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 10 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
