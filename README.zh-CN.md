# Yado

[English](README.md) · 简体中文 · [繁體中文](README.zh-TW.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Italiano](README.it.md)

**Yado** 的官方指南和反馈仓库，Yado 是在 Mac 上管理 iPhone 的原生 App，重复照片、大视频和不用的 App 一次清掉，整理主屏幕，传文件，备份留在自己的 Mac 上。

Yado 是付费 App，每一份购买都用在后续的开发和更新上，这个仓库放使用指南、问题和反馈，不包含 App 的源代码。

## 获取 Yado

| 系统要求 | 下载 | 使用指南 |
| --- | --- | --- |
| macOS 14 或更新版本，Apple 芯片和 Intel 都可以，手机需要 iPhone | [yado.house](https://yado.house/zh/?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme) | [帮助](https://yado.house/zh/help?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme) |

Yado 由 [Tw93](https://github.com/tw93) 开发和维护，用数据线连，配对过之后在同一个 Wi-Fi 下也能连，不用越狱、不用登录 Apple ID，也不用在手机上装 App。

![Yado 在 Mac 上的概览页](https://yado.house/img/shots/overview-zh.webp)

| 页面 | 能做什么 |
| --- | --- |
| 概览 | 电池健康、现在充电多少瓦、空间被什么占了、数据线够不够快，截屏还能自动套上手机外框 |
| 清理 | 重复照片、大视频、拍糊的照片和收据、停车位这类杂图放在一起看，每一项确认后才从手机上删 |
| 照片 | 按相簿或去过的地方浏览，原图导出到 Mac，相似照片每组留最好的一张 |
| App | 找出几周没打开、商店已下架、一年没更新的 App，勾上就能卸载，主屏幕按分类收进文件夹 |
| 文件 | 手机和 Mac 之间拖着传文件 |
| 备份 | 定时备份到 Mac 或外置硬盘，联系人、备忘录和信息都能逐条翻看，可以恢复到这台或另一台 iPhone |

### 开始使用

1. 从上面的官网下载 Yado，拖进「应用程序」后打开。
2. 用数据线连上 iPhone，解锁后在手机上点「信任」，之后想用 Wi-Fi 连，在 Yado 标志菜单（标签栏最左边那只燕子）里选「无线连接」。
3. 每个会改动手机的操作在购买前都能免费用两次，查看、扫描、浏览备份和做备份一直免费，买好后打开设置，在「通用」里点「Yado 授权」旁边的「管理授权」，粘贴 Dodo Payments 邮件里的授权码，再点「激活 Yado」。

[博客文章](https://yado.house/zh/blog?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme) · [更新日志](https://yado.house/zh/releases?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme)

### 推荐阅读

- [在 Mac 上管理 iPhone，系统工具和爱思助手怎么选](https://yado.house/zh/blog/manage-iphone-from-mac?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme)
- [iMazing 替代品怎么选，Mac 上按要做的事来比](https://yado.house/zh/blog/imazing-alternative?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme)
- [iPhone 删除重复照片，先用照片 App 合并](https://yado.house/zh/blog/delete-duplicate-photos-iphone?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme)
- [在 Mac 上查看 iPhone 备份内容，导出短信和联系人](https://yado.house/zh/blog/view-iphone-backup-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme)
- [iPhone 照片存到移动硬盘，不占 Mac 空间怎么做](https://yado.house/zh/blog/move-photos-iphone-to-external-drive?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme)
- [iPhone 主屏幕怎么整理：按名称排、分文件夹、常用放第一页](https://yado.house/zh/blog/organize-iphone-home-screen?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme)

## 反馈

- [反馈问题](https://github.com/tw93/Yado-App/issues/new?template=bug.yml)
- [提功能建议](https://github.com/tw93/Yado-App/issues/new?template=feature_request.yml)
- [提问或参与讨论](https://github.com/tw93/Yado-App/discussions)

Issue 和讨论都是公开的，购买、激活和退款的问题发邮件到 [hi@yado.house](mailto:hi@yado.house)，安全问题走[私下反馈渠道](.github/SECURITY.md)。

## 常见问题

### 有公开的 GitHub 仓库，是不是说明 Yado 开源？

不是，这个仓库只放文档和社区反馈，App 的源代码不公开。

### Yado 多少钱？

$19 美元买断，支持 2 台 Mac，没有订阅，之后的更新都免费，购买 14 天内用付款邮箱写信到 [hi@yado.house](mailto:hi@yado.house) 可以全额退款。

### 删照片会不会删错？

删掉的照片会进 iPhone 的最近删除，30 天内都能在手机上恢复，清理时搬到 Mac 的照片要先核对存下的是完整原图才会从手机上删，重复照片默认每组留下最好的一张。

### 会联网吗，会上传什么？

照片、文件和备份都不离开这台 Mac，联网只用来下载 App 分类表和 iOS 版本列表、核对授权、检查更新，以及崩溃后你同意时发送崩溃报告，手机里装了哪些 App 不会上传，详细说明在[隐私说明](https://yado.house/zh/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=yado-app-readme)里。

### 授权码在哪，换新 Mac 怎么办？

授权码由 Dodo Payments 发到结账时填的邮箱，可以在收件箱和垃圾邮件里搜 Dodo，还是找不到就用付款邮箱或 Payment ID 写信到 [hi@yado.house](mailto:hi@yado.house)，这些信息不要发到公开 Issue 里。一份授权能用在 2 台 Mac 上，两个名额都占满时，新 Mac 上会列出已激活的两台，解绑其中一台就能在新 Mac 上激活，旧 Mac 不在手边也可以。

### 哪个网站是官方的？

**yado.house** 是 Yado 唯一的官网，App Store 上的「Yado: Claude Code & Codex」是另一位开发者的 App，和这里没有关系。
