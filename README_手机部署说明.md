# 天津地铁模拟经营版（2026）— 手机部署说明

本目录内容可直接上传到 GitHub 仓库根目录，用 GitHub Pages 发布为静态网站。

## 上传前检查
- 解压后应直接看到 `index.html`、`css/`、`js/`、`img/` 等。
- 不要把整个外层文件夹再套一层上传；`index.html` 必须在仓库根目录。
- 保留 `LICENSE.txt`、`THIRD_PARTY_NOTICES.txt` 和 `licenses/`。

## GitHub Pages 发布
1. 在 GitHub 创建一个新的 Public 仓库，例如 `tianjin-metro`。
2. 进入仓库，选择 `Add file` → `Upload files`。
3. 上传本目录中的全部文件和文件夹，提交到 `main` 分支。
4. 进入 `Settings` → `Pages`。
5. `Build and deployment` 的 Source 选择 `Deploy from a branch`。
6. Branch 选择 `main`，目录选择 `/(root)`，点击 `Save`。
7. 等待部署完成，GitHub Pages 会显示可访问网址，格式为：
   `https://你的GitHub用户名.github.io/tianjin-metro/`

## 手机游玩
用手机浏览器打开 Pages 地址即可。建议横屏体验；也可在浏览器菜单中选择“添加到主屏幕”。

## 项目说明
这是基于原项目的非官方社区修改版。天津地图及线路坐标为游戏级近似表达，并非导航数据或官方规划文件。未来线路属于玩家自由规划设想。请阅读并遵守原项目许可证及第三方组件声明。
