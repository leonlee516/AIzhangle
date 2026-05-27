# AI涨乐移动端原型

这是一个可部署到 GitHub Pages 的静态 PWA 原型。iPhone 用户访问部署地址后，可以通过 Safari 的“分享”菜单选择“添加到主屏幕”，之后就能像独立 App 一样打开。

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库，例如 `ai-zhangle-demo`。
2. 上传本目录下的全部文件：`index.html`、`manifest.json`、`sw.js`、`icon.svg`、`apple-touch-icon.png`、`.nojekyll`。
3. 进入仓库 `Settings` -> `Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`，保存。
6. 等 GitHub Pages 发布完成，打开它给出的访问地址。

## iPhone 独立运行

1. 用 iPhone Safari 打开 GitHub Pages 地址。
2. 点击底部分享按钮。
3. 选择“添加到主屏幕”。
4. 从桌面图标打开，即可进入全屏独立运行模式。

## 说明

页面中的价格、胜率、收益和买卖点均为模拟展示，用于表达产品体验与合规包装方式，不构成实际投资建议。
部署触发：2026-05-27
