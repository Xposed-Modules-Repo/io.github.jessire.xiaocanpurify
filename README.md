# 小蚕净化 (XiaoCanPurify)

小蚕霸王餐 (`com.realtech.xiaocan`) 的 Xposed / LSPosed 净化模块, 使用 libxposed API 102.

## 最新版本

**2.0** (`versionCode=24`), 针对小蚕 3.21.2 (2985) 核对并测试.

- 内置「我的 → 设置 → 模块设置」入口与 38 个分项开关, 默认全开, 点按即保存.
- 新增首页「你有一单可免单」、周年庆品牌券弹窗拦截, 以及原生上传凭证页广告移除.
- 新增新店推荐任务成套屏蔽, 覆盖详情页自动跳转、订单任务网页与网页退出挽留, 手动入口保留.
- 新增提现成功页「关注公众号」推广自动关闭.
- 修复偶发的打开即闪退.
- 移除模块桌面图标与自带页面; 全局广告、弹窗和网络过滤保留.
- 底部仅保留首页、订单、我的.

完整更新内容见 [更新日志](CHANGELOG.md).

## 安装与更新

2.0 的签名与 1.2 不同, 请先卸载旧版模块, 再从 [Releases](https://github.com/Xposed-Modules-Repo/io.github.jessire.xiaocanpurify/releases) 下载并安装 `XiaoCanPurify-2.0-release.apk`.

在 LSPosed 中启用模块, 作用域勾选小蚕霸王餐, 强制停止并重新打开小蚕后生效. 模块设置入口位于小蚕「我的 → 设置 → 模块设置」.

## Source

[GitHub 源码](https://github.com/Jessire/XiaoCanPurify)
