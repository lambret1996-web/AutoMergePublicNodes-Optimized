# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 06:33:56 |
| 运行耗时 | 745.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 91522 |
| 去重后节点 | 24896 |
| TCP 可达 | 3000 |
| 真实可用 | 498 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24896 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 42.8 |
| probe | 271.6 |
| real_test | 327.3 |
| generate | 95.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53689 |
| vmess | 14837 |
| shadowsocks | 11297 |
| trojan | 9319 |
| hysteria2 | 1483 |
| http | 635 |
| shadowsocksr | 131 |
| socks | 85 |
| anytls | 21 |
| hysteria | 17 |
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
| 79.69 | shadowsocks | 256.1 | 711.6 | 21.85 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 37.19.198.160 |
| 79.69 | shadowsocks | 256.2 | 713.8 | 21.85 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 37.19.198.236 |
| 79.63 | shadowsocks | 258.8 | 720.6 | 21.79 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 37.19.198.244 |
| 78.17 | shadowsocks | 321.6 | 912.9 | 20.33 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 37.19.198.243 |
| 77.56 | shadowsocks | 218.5 | 590.2 | 22.72 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 198.98.53.130 |
| 76.67 | shadowsocks | 287.6 | 655.9 | 21.12 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 156.146.38.170 |
| 76.46 | shadowsocks | 286.0 | 650.4 | 21.16 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 156.146.38.169 |
| 76.38 | shadowsocks | 282.0 | 645.2 | 21.25 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.79 | hysteria2 | 387.8 | 860.0 | 18.8 | 0.0 | 10.0 | 14.21 | 17.7 | Au1rxx-base64 | 66.94.121.46 |
| 75.56 | vless | 244.0 | 690.5 | 22.13 | 0.0 | 10.0 | 5.73 | 17.7 | Au1rxx-base64 | 47.253.226.114 |
| 74.78 | shadowsocks | 311.1 | 875.9 | 20.58 | 0.0 | 9.11 | 14.52 | 17.7 | Au1rxx-base64 | 15.204.246.132 |
| 74.29 | vless | 259.4 | 641.1 | 21.77 | 0.0 | 9.09 | 5.73 | 17.7 | Au1rxx-base64 | 138.124.60.146 |
| 74.06 | vless | 246.4 | 692.2 | 22.07 | 0.0 | 9.04 | 5.73 | 17.7 | Au1rxx-base64 | 79.141.172.154 |
| 73.89 | hysteria2 | 317.9 | 899.3 | 20.42 | 0.0 | 10.0 | 14.21 | 10.36 | mheidari-all | 159.223.157.129 |
| 73.47 | vless | 289.6 | 710.0 | 21.07 | 0.0 | 8.97 | 5.73 | 17.7 | Au1rxx-base64 | 169.40.42.232 |
| 72.58 | vless | 333.9 | 867.9 | 20.05 | 0.0 | 9.1 | 5.73 | 17.7 | Au1rxx-base64 | 167.17.69.171 |
| 72.56 | shadowsocks | 317.3 | 617.3 | 20.43 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 108.181.118.10 |
| 72.5 | http | 307.4 | 858.0 | 20.66 | 0.0 | 10.0 | 10.38 | 13.96 | ermaozi | 52.55.81.168 |
| 72.46 | shadowsocks | 430.8 | 1158.0 | 17.8 | 0.0 | 8.94 | 14.52 | 17.7 | Au1rxx-base64 | 185.156.47.97 |
| 72.43 | shadowsocks | 409.0 | 1017.6 | 18.31 | 0.0 | 10.0 | 14.52 | 17.32 | Surfboard-tg-mixed | 51.222.200.165 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.912 | 0.848 | 302 | 1660 | prefer |
| ermaozi | 0.689 | 0.682 | 44 | 369 | observe |
| Surfboard-tg-mixed | 0.664 | 0.585 | 241 | 7043 | observe |
| mheidari-all | 0.476 | 0.395 | 167 | 19848 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| Epodonios-all | 0.255 | None | 0 | 7572 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9006 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5601 | observe |
| barry-far-vless | 0.255 | None | 0 | 5890 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1662 | observe |
| ermaozi-get_subscribe | 0.235 | 0.4 | 5 | 393 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 71 |
| geo | TimeoutError | - | 70 |
| speed | ClientOSError | - | 36 |
| speed | TimeoutError | - | 35 |
| 204 | TimeoutError | - | 31 |
| cn-block | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 20 |
| 204 | ClientOSError | - | 9 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40530: bind: address already in use | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
