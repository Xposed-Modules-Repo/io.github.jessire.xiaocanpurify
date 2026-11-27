# 小蚕净化 (XiaoCanPurify)

小蚕霸王餐 (`com.realtech.xiaocan`) 的 Xposed / LSPosed 净化模块, 使用 libxposed API 102.

## 最新版本

**2.1** (`versionCode=27`), 适配小蚕 3.23.0 (3070).

- 适配小蚕 3.23.0: 恢复「模块设置」入口和底栏「订单」标签, 拦截新版插屏/横幅广告、首页通知与会员弹窗、详情页促销气泡、福利页推广跳转及搜券退出挽留.
- 新增「屏蔽首页大牌券专享活动」(默认开启) 与「隐藏底栏『订单』」(默认关闭, 即时生效) 两项开关, 共 40 项.
- 首页去横幅后统一为浅橙底色, 修正顶部标志、城市名和搜索按钮显示.
- 修复设置页夜间模式文字对比度、底部重启图标, 以及网络超时和空配置引发的偶发崩溃.
- 保留模块设置页、全局广告/弹窗/网络过滤与报名外跳保护.

完整更新内容见 [更新日志](CHANGELOG.md).

## 安装与更新

2.1 与 2.0 签名一致, 已安装 2.0 可直接覆盖升级; 从 1.2 及更早版本升级仍需先卸载旧版.

从 [Releases](https://github.com/Xposed-Modules-Repo/io.github.jessire.xiaocanpurify/releases) 下载并安装 `XiaoCanPurify-2.1-release.apk`.

在 LSPosed 中启用模块, 作用域勾选小蚕霸王餐, 强制停止并重新打开小蚕后生效. 模块设置入口位于小蚕「我的 → 设置 → 模块设置」.

## Source

[GitHub 源码](https://github.com/Jessire/XiaoCanPurify)
