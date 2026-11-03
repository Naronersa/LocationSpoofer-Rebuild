# LocationSpoofer-Rebuild
A Rebuild Version of Former LocationSpoofer V3.0.0
## 来源 / Upstream
本项目基于原作者公开发布的 LocationSpoofer 3.0.0 源码（GPL-3.0）。独立社区重建版，不是官方版本，与原作者无隶属或背书关系。\
上游维护者（GitHub）：[HuangZhuoRui](https://github.com/HuangZhuoRui)\
上游 LICENSE 版权署名：SuseOAA\
上游仓库：[HuangZhuoRui/LocationSpoofer](https://github.com/HuangZhuoRui/LocationSpoofer)\
上游许可证：https://github.com/HuangZhuoRui/LocationSpoofer/blob/main/LICENSE
## 简介
Global 本地方案 Android 8.0+（arm64）KernelSU + Zygisk Next + LSPosed(Magisk + Zygisk/Zygisk Next + LSPosed未验证)\
LSPosed 作用域：system、com.android.phone、com.android.bluetooth\
包名&签名 SHA1 [SHA256SUMS.txt](SHA256SUMS.txt)
## 功能
添加并改进了一些功能
## 地图与 Key
无内置Key\
APK 内含第三方地图 SDK，受其各自条款约束\
没有 Key 时，底图有时仍能显示，但搜索、离线地图下载等功能需要 Key
## 限制
不同 ROM / 系统版本的 Native Hook 兼容性不同 只验证了小米10S(thyme)
## License
GPL-3.0 [LICENSE](LICENSE)\
源码包：[LocationSpoofer-rebuild-source.zip](LocationSpoofer-rebuild-source.zip)
