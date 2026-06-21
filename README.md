# 萍郷 · My Hometown

一个介绍我的家乡 —— 江西萍乡的单页静态网站。

A single-page static site introducing my hometown, Pingxiang, Jiangxi, China.

## 预览 / Preview

打开 `index.html` 即可在浏览器中查看，或部署到任意静态主机。

Open `index.html` in a browser, or deploy to any static host.

## 项目结构 / Structure

```
.
├── index.html      # 主页面（自包含的 HTML / CSS / JS bundle）
├── images/         # 图片资源
└── README.md
```

## 部署到 Vercel / Deploy to Vercel

本项目是纯静态站点，无需构建步骤。

This is a pure static site — no build step required.

1. 在 [vercel.com](https://vercel.com) 登录并点击 **Add New → Project**。
2. 选择 GitHub 仓库 `chloroplast11/my-hometown` 并导入。
3. **Framework Preset** 选择 `Other`，**Build Command** 留空，**Output Directory** 留空。
4. 点击 **Deploy**，Vercel 会直接把仓库根目录作为静态资源发布。

之后每次 `git push` 到 `main` 分支都会自动触发部署。

## 本地预览 / Local preview

```bash
# Python 3
python3 -m http.server 8000

# Node
npx serve .
```

然后访问 http://localhost:8000
