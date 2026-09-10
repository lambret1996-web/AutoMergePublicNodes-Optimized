# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 18:29:50 |
| 运行耗时 | 655.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89661 |
| 去重后节点 | 24417 |
| TCP 可达 | 3000 |
| 真实可用 | 386 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24417 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.5 |
| tcp | 41.7 |
| probe | 296.7 |
| real_test | 223.1 |
| generate | 85.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53843 |
| vmess | 13278 |
| shadowsocks | 11045 |
| trojan | 8751 |
| hysteria2 | 1955 |
| http | 568 |
| shadowsocksr | 127 |
| socks | 61 |
| hysteria | 15 |
| tuic | 10 |
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
| 82.85 | hysteria2 | 242.6 | 641.2 | 22.16 | 0.0 | 9.08 | 13.75 | 18.96 | Au1rxx-base64 | 159.223.157.129 |
| 81.59 | vless | 243.7 | 613.0 | 22.14 | 0.0 | 9.05 | 11.44 | 18.96 | Au1rxx-base64 | 195.123.235.177 |
| 81.22 | vless | 247.0 | 689.8 | 22.06 | 0.0 | 8.76 | 11.44 | 18.96 | Au1rxx-base64 | 79.141.172.154 |
| 81.21 | vless | 260.0 | 696.2 | 21.76 | 0.0 | 9.05 | 11.44 | 18.96 | Au1rxx-base64 | 47.253.226.114 |
| 80.61 | vless | 273.3 | 649.6 | 21.45 | 0.0 | 8.76 | 11.44 | 18.96 | Au1rxx-base64 | 169.40.42.179 |
| 80.6 | vless | 272.7 | 692.1 | 21.47 | 0.0 | 8.73 | 11.44 | 18.96 | Au1rxx-base64 | 167.17.69.171 |
| 79.78 | shadowsocks | 235.7 | 608.1 | 22.32 | 0.0 | 8.74 | 13.76 | 18.96 | Au1rxx-base64 | 198.98.53.130 |
| 79.51 | vless | 320.9 | 724.9 | 20.35 | 0.0 | 8.76 | 11.44 | 18.96 | Au1rxx-base64 | 169.40.42.90 |
| 79.39 | shadowsocks | 256.6 | 687.6 | 21.84 | 0.0 | 8.83 | 13.76 | 18.96 | Au1rxx-base64 | 37.19.198.243 |
| 79.36 | shadowsocks | 252.2 | 674.6 | 21.94 | 0.0 | 8.7 | 13.76 | 18.96 | Au1rxx-base64 | 37.19.198.160 |
| 79.07 | vless | 338.7 | 734.3 | 19.94 | 0.0 | 8.73 | 11.44 | 18.96 | Au1rxx-base64 | 169.40.42.212 |
| 78.84 | vless | 348.4 | 862.1 | 19.71 | 0.0 | 8.73 | 11.44 | 18.96 | Au1rxx-base64 | 169.40.42.229 |
| 78.8 | vless | 286.2 | 676.3 | 21.15 | 0.0 | 8.76 | 11.44 | 18.96 | Au1rxx-base64 | 169.40.42.35 |
| 78.56 | vless | 328.8 | 801.9 | 20.17 | 0.0 | 8.68 | 11.44 | 18.96 | Au1rxx-base64 | 66.70.179.198 |
| 78.35 | vless | 261.8 | 660.6 | 21.72 | 0.0 | 8.76 | 11.44 | 18.96 | Au1rxx-base64 | 169.40.42.74 |
| 78.29 | vless | 353.8 | 828.0 | 19.59 | 0.0 | 8.77 | 11.44 | 18.96 | Au1rxx-base64 | 169.40.42.231 |
| 78.22 | vless | 377.2 | 1002.5 | 19.05 | 0.0 | 8.77 | 11.44 | 18.96 | Au1rxx-base64 | 169.40.42.184 |
| 78.12 | shadowsocks | 252.4 | 676.2 | 21.94 | 0.0 | 10.0 | 13.76 | 16.42 | Surfboard-tg-mixed | 37.19.198.236 |
| 77.69 | vless | 301.9 | 734.2 | 20.79 | 0.0 | 8.79 | 11.44 | 18.96 | Au1rxx-base64 | 169.40.42.173 |
| 77.54 | shadowsocks | 308.9 | 777.7 | 20.63 | 0.0 | 8.69 | 13.76 | 18.96 | Au1rxx-base64 | 38.180.135.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.92 | 0.857 | 272 | 1657 | prefer |
| ermaozi | 0.785 | 0.792 | 24 | 405 | prefer |
| Surfboard-tg-mixed | 0.775 | 0.7 | 80 | 7221 | prefer |
| mheidari-all | 0.574 | 0.493 | 152 | 18727 | observe |
| tg-oneclickvpnkeys | 0.32 | 1.0 | 2 | 223 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7657 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8628 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5840 | observe |
| barry-far-vless | 0.255 | None | 0 | 6014 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3508 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1657 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 46 |
| cn-block | ClientOSError | - | 34 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 9 |
| geo | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| 204 | ProxyConnectionError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
