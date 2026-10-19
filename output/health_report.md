# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 18:38:02 |
| 运行耗时 | 622.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94583 |
| 去重后节点 | 26114 |
| TCP 可达 | 3000 |
| 真实可用 | 318 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26114 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.5 |
| tcp | 44.2 |
| probe | 277.7 |
| real_test | 210.8 |
| generate | 80.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56074 |
| vmess | 16894 |
| shadowsocks | 11477 |
| trojan | 7969 |
| hysteria2 | 1473 |
| http | 390 |
| shadowsocksr | 170 |
| socks | 67 |
| anytls | 46 |
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
| 82.49 | hysteria2 | 266.0 | 720.2 | 21.62 | 0.0 | 9.16 | 14.35 | 18.86 | Au1rxx-base64 | 129.213.91.185 |
| 80.7 | shadowsocks | 253.0 | 707.0 | 21.92 | 0.0 | 10.0 | 13.92 | 18.86 | Au1rxx-base64 | 37.19.198.244 |
| 80.11 | shadowsocks | 278.6 | 771.8 | 21.33 | 0.0 | 10.0 | 13.92 | 18.86 | Au1rxx-base64 | 37.19.198.160 |
| 79.16 | vless | 258.8 | 684.7 | 21.79 | 0.0 | 9.24 | 9.27 | 18.86 | Au1rxx-base64 | 167.17.69.171 |
| 78.93 | vless | 301.5 | 753.2 | 20.8 | 0.0 | 10.0 | 9.27 | 18.86 | Au1rxx-base64 | 66.70.179.198 |
| 78.84 | shadowsocks | 297.1 | 831.9 | 20.9 | 0.0 | 9.16 | 13.92 | 18.86 | Au1rxx-base64 | 37.19.198.243 |
| 78.22 | shadowsocks | 279.8 | 649.2 | 21.3 | 0.0 | 10.0 | 13.92 | 18.86 | Au1rxx-base64 | 156.146.38.167 |
| 77.88 | vless | 313.3 | 701.6 | 20.52 | 0.0 | 9.27 | 9.27 | 18.86 | Au1rxx-base64 | 169.40.42.90 |
| 77.88 | vless | 315.0 | 845.7 | 20.49 | 0.0 | 9.26 | 9.27 | 18.86 | Au1rxx-base64 | 169.40.42.225 |
| 77.69 | vless | 319.8 | 884.5 | 20.38 | 0.0 | 9.18 | 9.27 | 18.86 | Au1rxx-base64 | 159.89.87.21 |
| 77.59 | vless | 359.2 | 915.7 | 19.46 | 0.0 | 10.0 | 9.27 | 18.86 | Au1rxx-base64 | 169.40.42.229 |
| 77.47 | shadowsocks | 290.1 | 659.2 | 21.06 | 0.0 | 10.0 | 13.92 | 18.86 | Au1rxx-base64 | 156.146.38.169 |
| 77.34 | vless | 283.6 | 635.7 | 21.21 | 0.0 | 10.0 | 9.27 | 18.86 | Au1rxx-base64 | 169.40.42.163 |
| 77.0 | vless | 354.7 | 911.9 | 19.57 | 0.0 | 9.3 | 9.27 | 18.86 | Au1rxx-base64 | 169.40.42.168 |
| 76.83 | vless | 361.8 | 865.7 | 19.4 | 0.0 | 9.3 | 9.27 | 18.86 | Au1rxx-base64 | 169.40.42.231 |
| 76.49 | vless | 372.7 | 883.2 | 19.15 | 0.0 | 9.21 | 9.27 | 18.86 | Au1rxx-base64 | 169.40.42.224 |
| 76.27 | shadowsocks | 286.9 | 667.0 | 21.14 | 0.0 | 10.0 | 13.92 | 18.86 | Au1rxx-base64 | 156.146.38.170 |
| 75.85 | shadowsocks | 283.4 | 655.0 | 21.22 | 0.0 | 9.22 | 13.92 | 18.86 | Au1rxx-base64 | 156.146.38.168 |
| 75.42 | vless | 361.5 | 927.8 | 19.41 | 0.0 | 9.26 | 9.27 | 18.86 | Au1rxx-base64 | 169.40.42.104 |
| 75.36 | hysteria2 | 261.4 | 530.0 | 21.73 | 0.0 | 9.24 | 14.35 | 18.86 | Au1rxx-base64 | 179.255.104.98 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.852 | 0.79 | 362 | 1580 | prefer |
| mheidari-all | 0.701 | 0.63 | 27 | 23148 | prefer |
| zhangkai | 0.478 | 1.0 | 6 | 27 | observe |
| Surfboard-tg-mixed | 0.4 | 0.304 | 23 | 7064 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 86 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| Epodonios-all | 0.255 | None | 0 | 7406 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9916 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5579 | observe |
| barry-far-vless | 0.255 | None | 0 | 5654 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1580 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 27 |
| 204 | ProxyError | - | 14 |
| speed | TimeoutError | - | 12 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyConnectionError | - | 10 |
| cn-block | ClientOSError | - | 6 |
| geo | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
