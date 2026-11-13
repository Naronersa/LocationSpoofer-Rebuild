# LocationSpoofer-Rebuild
[中文](#来源) | [English](#source)
## 来源
本项目基于原作者公开发布的 LocationSpoofer 3.0.0 源码（GPL-3.0）。\
独立社区重建版，不是官方版本，与原作者无隶属或背书关系。\
上游维护者（GitHub）：[HuangZhuoRui](https://github.com/HuangZhuoRui)\
上游 LICENSE 版权署名：SuseOAA\
上游仓库：[HuangZhuoRui/LocationSpoofer](https://github.com/HuangZhuoRui/LocationSpoofer)\
上游许可证：https://github.com/HuangZhuoRui/LocationSpoofer/blob/main/LICENSE
## 简介
用于定位、路线和传感器模拟的技术研究及个人测试。
- Global Hook
- 本地方案
- Android 8.0+（arm64）
- KernelSU + Zygisk Next + LSPosed (Magisk + Zygisk/Zygisk Next + LSPosed未验证)
- LSPosed 作用域：system、com.android.phone、com.android.bluetooth
- 包名&签名 SHA1 [SHA256SUMS.txt](SHA256SUMS.txt)
- 下载 [Releases](https://github.com/Naronersa/LocationSpoofer-Rebuild/releases)
## 功能
添加并改进了一些功能
## 地图与 Key
无内置Key\
APK 内含第三方地图 SDK, 受其各自条款约束\
没有 Key 时，底图有时仍能显示, 但搜索、离线地图下载等功能需要 Key
## 限制
不同 ROM / 系统版本的 Native Hook 兼容性不同; 只验证了小米10S(thyme)\
模拟数据为合成数据, 不保证与真实设备一致, 也不保证通过所有第三方校验.
## License
GPL-3.0 [LICENSE](LICENSE)\
使用前请阅读 [DISCLAIMER](DISCLAIMER.md)\
源码包：[LocationSpoofer-rebuild-source.zip](LocationSpoofer-rebuild-source.zip)

---

## Source
This project is based on the publicly released LocationSpoofer 3.0.0 source code (GPL-3.0) by the original author.\
Independent community rebuild, not an official version, and not affiliated with or endorsed by the original author.\
Upstream maintainer (GitHub): [HuangZhuoRui](https://github.com/HuangZhuoRui)\
Upstream LICENSE copyright attribution: SuseOAA\
Upstream repository: [HuangZhuoRui/LocationSpoofer](https://github.com/HuangZhuoRui/LocationSpoofer)\
Upstream license: https://github.com/HuangZhuoRui/LocationSpoofer/blob/main/LICENSE
## Overview
For technical research and personal testing of location, route, and sensor simulation.
- Global Hook
- Local solution
- Android 8.0+ (arm64)
- KernelSU + Zygisk Next + LSPosed (Magisk + Zygisk/Zygisk Next + LSPosed unverified)
- LSPosed scope: system, com.android.phone, com.android.bluetooth
- Package name & signing SHA1 [SHA256SUMS.txt](SHA256SUMS.txt)
- Download [Releases](https://github.com/Naronersa/LocationSpoofer-Rebuild/releases)
## Features
Added and improved some features
## Maps and Keys
No built-in key.\
The APK contains third-party map SDKs, subject to their respective terms.\
Without a key, basemaps may sometimes still display, but features such as search and offline map downloads require a key.
## Limitations
Native Hook compatibility varies across ROMs / system versions. Only verified on Xiaomi 10S (thyme).\
Simulated data is synthetic and is not guaranteed to match real devices, nor is it guaranteed to pass any third-party validation.
## License
GPL-3.0 [LICENSE](LICENSE)\
Please read [DISCLAIMER](DISCLAIMER.md) before use.\
Source package: [LocationSpoofer-rebuild-source.zip](LocationSpoofer-rebuild-source.zip)
