# HeePic Website

HeePic（保险箱 / 私密相册）独立官网与法律页面。

本地可直接用浏览器打开 `index.html` 预览，无需构建。

## 当前线上（GitHub Pages）

公开站点仓库：[HeeBox/heepic-website](https://github.com/HeeBox/heepic-website)

| 页面 | URL |
|------|-----|
| 中文官网 | https://heebox.github.io/heepic-website/ |
| 英文官网 | https://heebox.github.io/heepic-website/en/ |
| 隐私政策 | https://heebox.github.io/heepic-website/privacy.html |
| 用户协议 | https://heebox.github.io/heepic-website/terms.html |
| 英文隐私 | https://heebox.github.io/heepic-website/privacy-en.html |
| 英文协议 | https://heebox.github.io/heepic-website/terms-en.html |

说明：HeeBox 组织 Free 套餐不支持「私有仓库 + Pages」。该站点仓库因此设为 **Public**，页面本身可公网访问（商店审核也需要）。源码只含官网静态页，不含 App 工程。

## 本地目录

| 文件 | 说明 |
|------|------|
| `index.html` | 中文官网 |
| `en/index.html` | 英文官网 |
| `privacy.html` / `privacy-en.html` | 隐私政策（中/英） |
| `terms.html` / `terms-en.html` | 用户协议（中/英） |
| `assets/` | 图标与截图 |

## 更新线上站点

在本目录改完后，同步推到 `HeeBox/heepic-website` 的 `main` 分支即可（Pages 自动发布）。

## 以后迁回 heebox.site

1. 上传本目录到服务器 `/heepic/`
2. 把 App 内 URL 从 `heebox.github.io/heepic-website/` 改回 `heebox.site/heepic/`

## 上架后待改

1. 首页「即将上架」换成正式商店链接
2. `HBAppFlavor.h` 填入 Apple ID
3. 运营邮箱：`heebox2025@heebox.site`
