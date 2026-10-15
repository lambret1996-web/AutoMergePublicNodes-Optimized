# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 03:50:46 |
| 运行耗时 | 715.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98808 |
| 去重后节点 | 27485 |
| TCP 可达 | 3000 |
| 真实可用 | 438 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27485 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.5 |
| tcp | 47.8 |
| probe | 261.6 |
| real_test | 325.1 |
| generate | 72.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58470 |
| vmess | 16368 |
| shadowsocks | 11789 |
| trojan | 10087 |
| hysteria2 | 1149 |
| http | 657 |
| shadowsocksr | 165 |
| socks | 68 |
| anytls | 32 |
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
| 79.7 | hysteria2 | 289.1 | 729.7 | 21.09 | 0.0 | 10.0 | 12.69 | 17.42 | Au1rxx-base64 | 129.213.91.185 |
| 79.43 | vless | 242.0 | 613.7 | 22.18 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 195.211.98.43 |
| 78.82 | shadowsocks | 242.8 | 609.7 | 22.16 | 0.0 | 10.0 | 13.24 | 17.42 | Au1rxx-base64 | 156.146.38.169 |
| 78.51 | shadowsocks | 255.9 | 642.1 | 21.85 | 0.0 | 10.0 | 13.24 | 17.42 | Au1rxx-base64 | 156.146.38.170 |
| 77.89 | shadowsocks | 283.0 | 755.8 | 21.23 | 0.0 | 10.0 | 13.24 | 17.42 | Au1rxx-base64 | 156.146.38.167 |
| 77.79 | vless | 256.1 | 620.2 | 21.85 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 216.227.161.95 |
| 76.89 | shadowsocks | 307.4 | 745.6 | 20.66 | 0.0 | 10.0 | 13.24 | 17.42 | Au1rxx-base64 | 37.19.198.160 |
| 76.71 | shadowsocks | 304.0 | 753.7 | 20.74 | 0.0 | 10.0 | 13.24 | 17.42 | Au1rxx-base64 | 37.19.198.244 |
| 75.69 | shadowsocks | 317.6 | 736.4 | 20.43 | 0.0 | 10.0 | 13.24 | 17.42 | Au1rxx-base64 | 64.74.163.67 |
| 75.68 | vless | 315.8 | 721.7 | 20.47 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 169.40.42.184 |
| 75.09 | shadowsocks | 310.7 | 734.5 | 20.59 | 0.0 | 10.0 | 13.24 | 17.42 | Au1rxx-base64 | 37.19.198.236 |
| 74.77 | vless | 325.0 | 748.2 | 20.25 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 159.89.87.21 |
| 74.24 | vless | 379.7 | 838.7 | 18.99 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 169.40.42.173 |
| 74.05 | vless | 313.4 | 746.3 | 20.52 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 47.253.226.114 |
| 74.03 | vless | 369.9 | 807.0 | 19.21 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 169.40.42.212 |
| 73.87 | vless | 281.0 | 666.6 | 21.27 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 69.48.201.136 |
| 73.61 | shadowsocks | 294.7 | 707.1 | 20.96 | 0.0 | 10.0 | 13.24 | 17.42 | Au1rxx-base64 | 140.82.63.79 |
| 73.48 | vless | 343.6 | 739.3 | 19.82 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 169.40.42.15 |
| 73.35 | shadowsocks | 302.8 | 611.2 | 20.77 | 0.0 | 10.0 | 13.24 | 17.42 | Au1rxx-base64 | 173.244.56.9 |
| 73.31 | vless | 332.4 | 725.1 | 20.08 | 0.0 | 10.0 | 9.83 | 17.42 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.942 | 0.881 | 421 | 1576 | prefer |
| ermaozi | 0.48 | 0.45 | 60 | 703 | observe |
| mheidari-all | 0.366 | 0.283 | 138 | 23886 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7681 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9917 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5728 | observe |
| barry-far-vless | 0.255 | None | 0 | 5978 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4271 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Surfboard-tg-mixed | 0.24 | 0.25 | 4 | 7169 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1576 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 76 |
| 204 | ProxyError | - | 36 |
| geo | ClientOSError | - | 29 |
| speed | ClientOSError | - | 14 |
| 204 | TimeoutError | - | 13 |
| speed | TimeoutError | - | 10 |
| cn-block | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
