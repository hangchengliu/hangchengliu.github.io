# 刘航成的个人主页

网站：https://hangchengliu.github.io

这是一个无需安装依赖、无需构建的静态个人主页，支持手机和电脑。

## 修改内容

编辑 `index.html` 即可修改姓名、介绍、项目和样式。可以在 GitHub 文件页面点击编辑按钮，保存到 `main` 分支后，GitHub Pages 会自动更新。

## 本地预览

直接用浏览器打开 `index.html`，或者在此目录运行 `python3 -m http.server 8000`，访问 http://localhost:8000。

## 部署

仓库 Settings → Pages → Deploy from a branch，选择 `main` 分支和 `/ (root)`。

## 这一版

- 首页和「关于」写明了正在做的 BlinkLane
- 项目区放上 BlinkLane，并保留这个主页
- 加上分享链接时的标题和描述、标签图标，以及找不到页面时的 `404.html`

## 还需要在 GitHub 网页上改的

仓库改不了个人资料。打开 GitHub 头像 → Settings → Profile：

- Website 填 `https://hangchengliu.github.io`
- Bio 可先写：做 BlinkLane，一个留在本地的 Tesla 行车记录复核工具。

## 后续可以添加

- 更具体的个人经历
- 项目截图
- 文章和学习记录
- 自定义域名
