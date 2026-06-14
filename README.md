# BILI-TV

一个面向 Android 4.4+（API 19+）老电视盒子的哔哩哔哩电视客户端学习项目。

---

## Release

### 当前版本

* 发布页：[`BILI-TV-20260614-V4.0`](https://github.com/k1moj1s/BILI/releases/tag/BILI-TV-20260614-V4.0)
* V4.0 下载（原始）：[BILI-TV-20260614-V4.0.apk](https://github.com/k1moj1s/BILI-TV/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)
* V4.0 下载（镜像地址1）：[BILI-TV-20260614-V4.0.apk](https://gh.idayer.com/https://github.com/k1moj1s/BILI/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)
* V4.0 下载（镜像地址2）：[BILI-TV-20260614-V4.0.apk](https://ghfile.geekertao.top/https://github.com/k1moj1s/BILI/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)
* V4.0 下载（镜像地址3）：[BILI-TV-20260614-V4.0.apk](https://gh.xxooo.cf/https://github.com/k1moj1s/BILI/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)
* V4.0 下载（镜像地址4）：[BILI-TV-20260614-V4.0.apk](https://xget.xi-xu.me/gh/k1moj1s/BILI/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)
* V4.0 下载（镜像地址5）：[BILI-TV-20260614-V4.0.apk](https://gh.zwy.one/https://github.com/k1moj1s/BILI-TV/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)
* V4.0 下载（镜像地址6）：[BILI-TV-20260614-V4.0.apk](https://https://cors.isteed.cc/github.com/k1moj1s/BILI-TV/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)
* V4.0 下载（镜像地址7）：[BILI-TV-20260614-V4.0.apk](https://ghp.keleyaa.com/https://github.com/k1moj1s/BILI-TV/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)
* V4.0 下载（镜像地址8）：[BILI-TV-20260614-V4.0.apk](https://gh.h233.eu.org/https://github.com/k1moj1s/BILI-TV/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)
* V4.0 下载（镜像地址9）：[BILI-TV-20260614-V4.0.apk](https://edgeone.gh-proxy.org/https://github.com/k1moj1s/BILI-TV/releases/download/BILI-TV-20260614-V4.0/BILI-TV-20260614-V4.0.apk)

* sha256:e0a14a3c1bff46fe8435a71cfcdba6781787cac29602213737959ff24c782c83

---

## 项目说明

由于目前很多BiliBili TV 客户端已经不再兼容 Android 4.4（API 19）及部分老旧电视盒子，因此本项目尝试在较低版本 Android 环境下进行兼容性开发、交互适配与播放能力研究。

本项目定位为学习与实验用途，主要关注：

* 老旧电视盒子的基础可用性
* Android TV 焦点与遥控器交互逻辑
* 视频播放链路与回退策略
* 低版本 Android 下的播放器兼容
* 较低内存设备上的列表、图片与页面响应优化

项目仍处于持续迭代阶段，代码和接口行为可能随时变化，不承诺长期稳定可用。

---

## 当前包含内容

* TV 侧边导航：首页、搜索、分区、动态、直播、我的、设置
* 首页推荐流与多标签内容浏览（推荐、综合热门、每周必看、入站必刷、全站音乐榜）
* 搜索、热搜、搜索联想与搜索历史
* 分区内容浏览，支持普通视频与部分 PGC 内容跳转
* 动态页浏览，支持关注 UP 视频内容切换
* 直播推荐、直播分区、关注直播间浏览
* 扫码登录
* 我的页面：历史记录、收藏夹、稍后再看、退出登录
* 视频播放：画质切换、编码选择、音轨/音质选择、倍速、选集、直播线路切换
* 视频弹幕与直播弹幕基础支持
* 遥控器焦点操作与菜单交互优化
* Android 4.4 基础兼容
* 部分低内存优化、缓存管理与视频流多链路回退

---

## 项目特性

### 1. 面向老设备

项目以 Android 4.4+（API 19+）设备为主要适配目标，重点关注老旧电视盒子、低内存环境和遥控器输入场景。

### 2. TV 交互优先

整体交互围绕 D-Pad 遥控器设计，重点处理焦点移动、菜单操作、播放器控制和页面切换体验。

### 3. 播放链路实验

项目针对视频播放地址获取、回退策略、登录态与公开链路兼容、播放失败重试等场景进行了较多实验性实现，用于研究不同设备与环境下的可用性问题。

### 4. 轻量化方向

项目持续进行代码清理、依赖精简和播放器模块调整，以减少安装包体积并降低老设备运行负担。

---

## 兼容性说明

理论支持环境：

* Android 4.4 及以上
* API 19+
* 支持 D-Pad 遥控器输入的电视或电视盒子

但在不同 ROM、芯片、系统裁剪环境下，可能出现：

* 登录异常
* 播放异常
* 焦点错乱
* 部分页面显示问题
* 某些视频无法获取播放地址

这类问题在老设备和非标准系统环境中都属于正常风险范围。

---

## 开发环境

* Android API 19+
* Java
* RecyclerView
* VLC for Android
* OkHttp
* Protobuf Lite
* Conscrypt

---

## 适用场景

本项目仅适合以下用途：

* 技术学习
* Android TV UI 研究
* 老设备兼容性实验
* 播放器行为测试
* 遥控器交互研究
* 视频流获取策略研究

不建议将本项目视为正式产品或稳定商用客户端。

---

## 使用提醒

由于第三方接口、登录状态、风控策略、版权策略与网络环境都可能随时变化，项目在不同时间与不同设备上的表现可能并不一致。

项目可能出现：

* 无法使用
* 接口失效
* 登录异常
* 播放异常
* 被限制访问
* 高画质获取失败

请自行评估使用风险。

---

## 声明

本项目仅供学习与技术研究使用。

项目本身不提供任何视频资源、账号资源或服务器资源，所有内容均来自用户自行访问的公开网络接口。

请勿用于：

* 商业用途
* 非法传播
* 盈利行为
* 破解行为
* 大规模分发

请勿在国内主流平台传播、推广或引流，包括但不限于：

* 哔哩哔哩
* 抖音
* 快手
* 小红书
* 微博
* 各类公众号平台

避免对项目与相关平台造成不必要影响。

如果相关权利方认为项目存在问题，请联系处理。

---

## 风险说明

由于第三方接口、风控机制、版权策略与平台行为随时可能调整，项目不保证持续可用，也不保证所有功能始终稳定。

开发者不对任何使用行为及其后果负责。

请在了解项目定位和风险前提下自行使用。

---

## License

项目代码采用 MIT License 发布。

本仓库内容仍以学习交流、技术研究和适配实验为主要目的，请结合上文声明与风险说明自行判断使用场景。


# MIT License

仅供学习交流使用。
