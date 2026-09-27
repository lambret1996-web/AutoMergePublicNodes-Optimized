# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 21:22:16 |
| 运行耗时 | 488.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96200 |
| 去重后节点 | 26758 |
| TCP 可达 | 3000 |
| 真实可用 | 328 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26758 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.4 |
| tcp | 43.7 |
| probe | 234.9 |
| real_test | 124.9 |
| generate | 76.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58740 |
| vmess | 14866 |
| shadowsocks | 11358 |
| trojan | 8923 |
| hysteria2 | 1451 |
| http | 573 |
| shadowsocksr | 170 |
| socks | 72 |
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
| 78.04 | vless | 244.2 | 697.5 | 22.13 | 0.0 | 9.26 | 9.89 | 16.76 | Au1rxx-base64 | 79.141.172.154 |
| 77.51 | vless | 268.5 | 711.0 | 21.56 | 0.0 | 9.3 | 9.89 | 16.76 | Au1rxx-base64 | 169.40.42.104 |
| 77.36 | vless | 272.8 | 661.3 | 21.46 | 0.0 | 9.28 | 9.89 | 16.76 | Au1rxx-base64 | 169.40.42.75 |
| 77.34 | shadowsocks | 253.6 | 704.3 | 21.91 | 0.0 | 10.0 | 13.55 | 15.88 | Surfboard-tg-mixed | 37.19.198.244 |
| 77.27 | shadowsocks | 256.6 | 710.7 | 21.84 | 0.0 | 10.0 | 13.55 | 15.88 | Surfboard-tg-mixed | 37.19.198.160 |
| 77.25 | vless | 283.4 | 715.3 | 21.22 | 0.0 | 9.38 | 9.89 | 16.76 | Au1rxx-base64 | 66.70.179.198 |
| 77.19 | vless | 282.3 | 691.3 | 21.24 | 0.0 | 9.3 | 9.89 | 16.76 | Au1rxx-base64 | 169.40.42.182 |
| 77.15 | vless | 284.2 | 700.1 | 21.2 | 0.0 | 9.3 | 9.89 | 16.76 | Au1rxx-base64 | 169.40.42.179 |
| 77.09 | shadowsocks | 264.4 | 714.4 | 21.66 | 0.0 | 10.0 | 13.55 | 15.88 | Surfboard-tg-mixed | 37.19.198.243 |
| 77.08 | shadowsocks | 264.7 | 716.2 | 21.65 | 0.0 | 10.0 | 13.55 | 15.88 | Surfboard-tg-mixed | 37.19.198.236 |
| 77.02 | vless | 247.7 | 696.9 | 22.04 | 0.0 | 9.33 | 9.89 | 16.76 | Au1rxx-base64 | 47.253.144.114 |
| 76.91 | shadowsocks | 261.0 | 662.0 | 21.74 | 0.0 | 9.36 | 13.55 | 16.76 | Au1rxx-base64 | 38.180.135.156 |
| 76.9 | vless | 293.6 | 661.0 | 20.98 | 0.0 | 9.27 | 9.89 | 16.76 | Au1rxx-base64 | 169.40.42.232 |
| 76.79 | shadowsocks | 255.6 | 665.3 | 21.86 | 0.0 | 10.0 | 13.55 | 15.88 | Surfboard-tg-mixed | 140.82.63.79 |
| 76.77 | vless | 305.8 | 850.4 | 20.7 | 0.0 | 9.42 | 9.89 | 16.76 | Au1rxx-base64 | 159.89.87.21 |
| 76.69 | vless | 304.2 | 689.3 | 20.74 | 0.0 | 9.3 | 9.89 | 16.76 | Au1rxx-base64 | 169.40.42.212 |
| 76.05 | vless | 287.2 | 769.7 | 21.13 | 0.0 | 9.27 | 9.89 | 16.76 | Au1rxx-base64 | 169.40.42.184 |
| 76.03 | vless | 335.5 | 709.6 | 20.01 | 0.0 | 9.37 | 9.89 | 16.76 | Au1rxx-base64 | 169.40.42.74 |
| 76.01 | vless | 245.9 | 696.8 | 22.09 | 0.0 | 9.27 | 9.89 | 16.76 | Au1rxx-base64 | 47.90.153.88 |
| 75.89 | vless | 338.7 | 791.4 | 19.94 | 0.0 | 9.3 | 9.89 | 16.76 | Au1rxx-base64 | 169.40.42.163 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.966 | 0.896 | 77 | 22680 | prefer |
| Surfboard-tg-mixed | 0.95 | 0.878 | 98 | 7018 | prefer |
| Au1rxx-base64 | 0.941 | 0.879 | 174 | 1652 | prefer |
| ermaozi | 0.539 | 0.529 | 34 | 289 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6752 | observe |
| tg-oneclickvpnkeys | 0.256 | 1.0 | 1 | 13 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7540 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9353 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5592 | observe |
| barry-far-vless | 0.255 | None | 0 | 5823 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4185 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1652 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 16 |
| 204 | ProxyConnectionError | - | 12 |
| 204 | TimeoutError | - | 8 |
| geo | TimeoutError | - | 8 |
| 204 | ProxyError | - | 6 |
| speed | TimeoutError | - | 3 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
