# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-10 17:18:32 |
| 运行耗时 | 827.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98017 |
| 去重后节点 | 27210 |
| TCP 可达 | 3000 |
| 真实可用 | 461 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27210 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.6 |
| tcp | 47.1 |
| probe | 351.9 |
| real_test | 344.7 |
| generate | 77.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57888 |
| vmess | 15684 |
| shadowsocks | 11664 |
| trojan | 10485 |
| hysteria2 | 1486 |
| http | 519 |
| shadowsocksr | 164 |
| socks | 72 |
| anytls | 32 |
| hysteria | 16 |
| tuic | 7 |

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
| 82.34 | hysteria2 | 271.2 | 705.3 | 21.5 | 0.0 | 10.0 | 13.75 | 19.64 | Au1rxx-base64 | 129.213.91.185 |
| 81.48 | shadowsocks | 244.7 | 596.2 | 22.11 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 156.146.38.167 |
| 81.48 | shadowsocks | 244.9 | 639.1 | 22.11 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 156.146.38.168 |
| 81.45 | shadowsocks | 246.1 | 601.4 | 22.08 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 156.146.38.169 |
| 81.37 | hysteria2 | 271.3 | 267.5 | 21.5 | 4.97 | 9.32 | 13.75 | 19.64 | Au1rxx-base64 | vp3.yysyy.online |
| 81.3 | shadowsocks | 252.5 | 633.0 | 21.93 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 156.146.38.170 |
| 80.78 | hysteria2 | 270.4 | 267.7 | 21.52 | 4.96 | 9.63 | 13.75 | 19.64 | Au1rxx-base64 | 45.32.10.7 |
| 80.23 | hysteria2 | 295.0 | 290.0 | 20.95 | 4.12 | 9.63 | 13.75 | 19.64 | Au1rxx-base64 | 158.101.148.79 |
| 79.98 | shadowsocks | 309.4 | 742.0 | 20.61 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 37.19.198.244 |
| 79.7 | shadowsocks | 305.2 | 748.9 | 20.71 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 37.19.198.243 |
| 79.03 | hysteria2 | 300.8 | 278.1 | 20.82 | 4.57 | 8.65 | 13.75 | 19.64 | Au1rxx-base64 | open.2ml.bid |
| 78.85 | shadowsocks | 329.3 | 817.4 | 20.16 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 37.19.198.236 |
| 77.54 | shadowsocks | 301.0 | 698.8 | 20.81 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 140.82.63.79 |
| 75.66 | shadowsocks | 335.3 | 770.9 | 20.02 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 5.78.51.123 |
| 74.04 | shadowsocks | 328.8 | 870.0 | 20.17 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 66.23.205.83 |
| 73.37 | shadowsocks | 327.9 | 760.7 | 20.19 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 64.74.163.69 |
| 72.37 | vless | 286.9 | 685.9 | 21.14 | 0.0 | 10.0 | 6.19 | 19.64 | Au1rxx-base64 | 69.48.201.136 |
| 72.32 | vless | 301.6 | 730.4 | 20.8 | 0.0 | 10.0 | 6.19 | 19.64 | Au1rxx-base64 | 172.245.253.16 |
| 72.26 | vless | 408.1 | 1017.4 | 18.33 | 0.0 | 10.0 | 6.19 | 19.64 | Au1rxx-base64 | 185.95.231.156 |
| 72.18 | shadowsocks | 329.5 | 699.4 | 20.15 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.931 | 0.858 | 374 | 1857 | prefer |
| mheidari-all | 0.807 | 0.736 | 53 | 23714 | prefer |
| Surfboard-tg-mixed | 0.673 | 0.595 | 121 | 7171 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 174 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7647 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9352 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5676 | observe |
| barry-far-vless | 0.255 | None | 0 | 5914 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1857 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 34 |
| 204 | TimeoutError | - | 33 |
| 204 | ProxyError | - | 31 |
| geo | ClientOSError | - | 14 |
| 204 | ClientOSError | - | 10 |
| speed | ClientOSError | - | 9 |
| speed | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
