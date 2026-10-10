# 小蚕净化 (XiaoCanPurify)

小蚕霸王餐 (`com.realtech.xiaocan`) 的 Xposed / LSPosed 净化模块, 使用 libxposed API 102.

## 最新版本

**1.2** (`versionCode=3`), 针对小蚕 3.21.2 核对并测试.

- 过滤开屏、信息流、插屏及运营弹窗.
- 补全提现页与提现完成后的弹窗广告位 (`WITHDRAWAL_SUCCESS_POPUP`、`WITHDRAWALPAGE_POPUP`、`8876` 等) 过滤.
- 保留普通下拉刷新, 只屏蔽下拉进入第二层.
- 隐藏会员轮播、详情广告和“分享赚豆”浮动入口.
- 增加报名自动外跳保护及淘宝安装领红包提示拦截.
- 底部仅保留首页、订单、我的.

完整更新内容见 [更新日志](CHANGELOG.md).

## 安装与更新

从 [Releases](https://github.com/Xposed-Modules-Repo/io.github.jessire.xiaocanpurify/releases) 下载并覆盖安装 APK, 在 LSPosed 中启用模块, 作用域勾选小蚕霸王餐. 强制停止并重新打开小蚕后生效, 无需卸载旧版或清除数据.

## Source

[GitHub 源码](https://github.com/Jessire/XiaoCanPurify)
