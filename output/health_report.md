# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-02 04:45:46 |
| 运行耗时 | 724.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98599 |
| 去重后节点 | 27531 |
| TCP 可达 | 3000 |
| 真实可用 | 444 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27531 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.5 |
| tcp | 47.5 |
| probe | 251.9 |
| real_test | 336.1 |
| generate | 80.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60065 |
| vmess | 15752 |
| shadowsocks | 11576 |
| trojan | 8980 |
| hysteria2 | 1427 |
| http | 509 |
| shadowsocksr | 168 |
| socks | 61 |
| anytls | 35 |
| hysteria | 17 |
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
| 83.01 | hysteria2 | 296.6 | 734.9 | 20.91 | 0.0 | 10.0 | 13.2 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 81.44 | hysteria2 | 307.1 | 724.4 | 20.67 | 0.0 | 10.0 | 13.2 | 20.0 | Au1rxx-base64 | 192.255.128.123 |
| 80.59 | shadowsocks | 245.7 | 603.4 | 22.09 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.46 | shadowsocks | 251.4 | 622.3 | 21.96 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 79.44 | hysteria2 | 278.3 | 608.3 | 21.34 | 0.0 | 10.0 | 13.2 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 79.25 | shadowsocks | 280.8 | 707.7 | 21.28 | 0.0 | 9.97 | 12.5 | 20.0 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 78.98 | vless | 291.2 | 731.5 | 21.04 | 0.0 | 10.0 | 7.94 | 20.0 | Au1rxx-base64 | 79.141.172.154 |
| 78.92 | vless | 285.7 | 690.9 | 21.16 | 0.0 | 10.0 | 7.94 | 20.0 | Au1rxx-base64 | 198.251.78.29 |
| 78.34 | shadowsocks | 305.5 | 752.6 | 20.71 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 78.04 | shadowsocks | 334.1 | 872.0 | 20.04 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 185.156.47.97 |
| 77.06 | shadowsocks | 376.7 | 929.5 | 19.06 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 15.204.247.206 |
| 77.05 | shadowsocks | 303.3 | 751.7 | 20.76 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 77.01 | shadowsocks | 364.9 | 937.0 | 19.33 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 161.129.71.149 |
| 76.32 | shadowsocks | 261.2 | 565.1 | 21.73 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 104.192.225.106 |
| 76.01 | shadowsocks | 341.7 | 805.0 | 19.87 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 140.82.63.79 |
| 75.75 | vless | 324.8 | 688.7 | 20.26 | 0.0 | 10.0 | 7.94 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 75.43 | vless | 318.7 | 750.2 | 20.4 | 0.0 | 10.0 | 7.94 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 75.3 | shadowsocks | 299.7 | 631.2 | 20.84 | 0.0 | 10.0 | 12.5 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 75.09 | vless | 385.8 | 823.4 | 18.85 | 0.0 | 10.0 | 7.94 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 75.05 | vless | 337.8 | 742.3 | 19.96 | 0.0 | 10.0 | 7.94 | 20.0 | Au1rxx-base64 | 159.89.87.21 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | 0.9 | 260 | 1731 | prefer |
| ermaozi | 0.909 | 0.917 | 24 | 618 | prefer |
| Surfboard-tg-mixed | 0.818 | 0.741 | 170 | 7165 | prefer |
| mheidari-all | 0.34 | 0.258 | 217 | 23308 | observe |
| ermaozi-get_subscribe | 0.339 | 0.75 | 4 | 475 | observe |
| DeltaKronecker-all | 0.337 | 0.429 | 7 | 5603 | observe |
| Epodonios-all | 0.255 | None | 0 | 7654 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9200 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5778 | observe |
| barry-far-vless | 0.255 | None | 0 | 6015 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4310 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1731 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 105 |
| speed | TimeoutError | - | 49 |
| geo | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 12 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 179 | 300 | - |
| global | False | 186 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
