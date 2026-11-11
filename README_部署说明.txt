# 《苏联的游戏：七日之盟》Build 03 网页版

这是一个可部署到静态网站托管服务的网页游戏包。

## 文件
- `index.html`：游戏主体
- `manifest.webmanifest`：添加到主屏幕所需配置
- `sw.js`：部署后缓存游戏文件，支持离线再次打开
- `icon.svg`：网页图标

## 部署到 GitHub Pages（免费）
1. 登录 GitHub，创建一个新仓库，例如 `soviet-game`。
2. 将本文件夹内的 **四个文件** 上传到仓库根目录（不是把 ZIP 再上传进去）。
3. 打开仓库 `Settings` → `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/ (root)`，点击 `Save`。
6. 等待 GitHub Pages 发布，页面会给出网址，格式通常为：
   `https://你的用户名.github.io/soviet-game/`

## iPhone 安装
网页发布后，用 Safari 打开上面的网址，点分享按钮，再选“添加到主屏幕”。

## 说明
当前环境可以生成并验证网页文件，但不能替用户登录 GitHub 或替用户创建公开托管地址。首次发布需要由你在 GitHub 完成一次上传和 Pages 开启。
