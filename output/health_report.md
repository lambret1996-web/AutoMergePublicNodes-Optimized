# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-29 22:15:50 |
| 运行耗时 | 437.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96969 |
| 去重后节点 | 27167 |
| TCP 可达 | 3000 |
| 真实可用 | 359 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27167 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.5 |
| tcp | 44.3 |
| probe | 208.0 |
| real_test | 129.2 |
| generate | 47.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59108 |
| vmess | 15092 |
| shadowsocks | 11359 |
| trojan | 9150 |
| hysteria2 | 1388 |
| http | 584 |
| shadowsocksr | 168 |
| socks | 73 |
| anytls | 24 |
| hysteria | 15 |
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
| 82.02 | vless | 227.7 | 592.7 | 22.51 | 0.0 | 10.0 | 11.19 | 18.32 | Au1rxx-base64 | 195.123.235.177 |
| 81.5 | hysteria2 | 250.9 | 684.0 | 21.97 | 0.0 | 10.0 | 13.33 | 19.3 | mheidari-all | 159.223.157.129 |
| 80.92 | vless | 238.3 | 677.9 | 22.26 | 0.0 | 9.15 | 11.19 | 18.32 | Au1rxx-base64 | 79.141.172.154 |
| 80.66 | vless | 281.6 | 632.2 | 21.26 | 0.0 | 10.0 | 11.19 | 19.3 | mheidari-all | 216.227.161.95 |
| 80.53 | vless | 255.6 | 726.7 | 21.86 | 0.0 | 9.16 | 11.19 | 18.32 | Au1rxx-base64 | 47.90.153.88 |
| 80.34 | vless | 266.6 | 652.9 | 21.61 | 0.0 | 9.22 | 11.19 | 18.32 | Au1rxx-base64 | 169.40.42.104 |
| 80.04 | vless | 281.8 | 707.6 | 21.25 | 0.0 | 9.28 | 11.19 | 18.32 | Au1rxx-base64 | 66.70.179.198 |
| 79.95 | vless | 280.3 | 678.5 | 21.29 | 0.0 | 9.15 | 11.19 | 18.32 | Au1rxx-base64 | 169.40.42.95 |
| 79.39 | vless | 282.4 | 692.9 | 21.24 | 0.0 | 9.22 | 11.19 | 18.32 | Au1rxx-base64 | 169.40.42.52 |
| 79.11 | vless | 322.7 | 820.2 | 20.31 | 0.0 | 9.29 | 11.19 | 18.32 | Au1rxx-base64 | 169.40.42.74 |
| 79.07 | vless | 314.6 | 871.0 | 20.49 | 0.0 | 9.07 | 11.19 | 18.32 | Au1rxx-base64 | 159.89.87.21 |
| 79.03 | vless | 310.6 | 705.9 | 20.59 | 0.0 | 9.13 | 11.19 | 18.32 | Au1rxx-base64 | 169.40.42.212 |
| 78.9 | shadowsocks | 311.5 | 894.8 | 20.57 | 0.0 | 10.0 | 13.53 | 19.3 | mheidari-all | 15.204.247.206 |
| 78.89 | vless | 326.6 | 900.4 | 20.22 | 0.0 | 9.16 | 11.19 | 18.32 | Au1rxx-base64 | 185.95.231.156 |
| 78.85 | shadowsocks | 254.4 | 711.3 | 21.89 | 0.0 | 9.11 | 13.53 | 18.32 | Au1rxx-base64 | 37.19.198.243 |
| 78.85 | vless | 317.6 | 723.8 | 20.43 | 0.0 | 9.22 | 11.19 | 18.32 | Au1rxx-base64 | 169.40.42.231 |
| 78.8 | shadowsocks | 256.0 | 716.4 | 21.85 | 0.0 | 9.1 | 13.53 | 18.32 | Au1rxx-base64 | 37.19.198.236 |
| 78.77 | vless | 334.9 | 913.5 | 20.03 | 0.0 | 9.23 | 11.19 | 18.32 | Au1rxx-base64 | 169.40.42.179 |
| 78.71 | shadowsocks | 257.5 | 713.0 | 21.82 | 0.0 | 9.04 | 13.53 | 18.32 | Au1rxx-base64 | 37.19.198.244 |
| 78.68 | vless | 338.0 | 861.3 | 19.95 | 0.0 | 9.22 | 11.19 | 18.32 | Au1rxx-base64 | 169.40.42.16 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.914 | 0.844 | 270 | 1792 | prefer |
| mheidari-all | 0.896 | 0.821 | 112 | 22763 | prefer |
| ermaozi | 0.826 | 0.84 | 25 | 291 | prefer |
| DeltaKronecker-all | 0.489 | 0.667 | 9 | 5528 | observe |
| Surfboard-tg-mixed | 0.489 | 0.833 | 6 | 7082 | observe |
| ermaozi-get_subscribe | 0.37 | 1.0 | 3 | 293 | observe |
| tg-oneclickvpnkeys | 0.36 | 1.0 | 3 | 62 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5314 | observe |
| Epodonios-all | 0.255 | None | 0 | 7556 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9172 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5695 | observe |
| barry-far-vless | 0.255 | None | 0 | 5942 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 17 |
| speed | TimeoutError | - | 6 |
| 204 | TimeoutError | - | 6 |
| 204 | ProxyError | - | 5 |
| geo | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
