# Orion Store 中文版（非官方构建）

这是 [RookieEnough/Orion-Store](https://github.com/RookieEnough/Orion-Store) 简体中文界面的**社区非官方编译版**，不是上游官方发布，请勿当作官方版本分发。

- 源码：本仓库 `hotfix/i18n-string-extraction` 分支（上游未合并的 i18n 分支 + 本仓库的编译修复）
- 许可：GPL-3.0，与上游一致；修改仅为修复编译错误和新增本构建工作流
- 上游作者：RookieEnough (RookieZ)，翻译由上游 i18n 分支与 Crowdin 项目提供

## 安装说明

1. 该 APK 使用**一次性自签名证书**，与官方 APK 签名不同。若手机上已装官方版，需先卸载（会丢失本地设置）。
2. 安装后进入 **Settings › Interface/语言（Language）**，选择「中文」。
3. 商店里的 App 名称与描述来自 Orion-Data 数据仓库，仍为英文，属正常现象。

## 已知问题

- 上游 i18n 分支本身尚未合并，后续上游若改动界面，本构建可能落后。
- 无自动更新通道，需手动下载新版本（签名会变，需卸载重装）。
