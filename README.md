# 淘宝潮流宣传站

互动视频产品展示网站，使用原生 HTML、CSS 和 JavaScript。

## 本地预览

在项目目录运行 `python3 -m http.server 8000`，然后打开 http://localhost:8000。

## GitHub Pages 部署

上传 `index.html`、`.nojekyll` 和首页引用的 `assets/` 文件，保持原有目录结构。

在 GitHub 仓库的 Settings → Pages 中选择：

- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

保存后等待 GitHub 完成部署。后续将网站修改推送至 `main` 分支即可自动更新。

视频采用相对路径，支持 GitHub Pages 项目子路径。字体来自外部 CDN，无法加载时自动使用系统字体。
