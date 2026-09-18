# 门神模拟器

一款在球门中画出扑救姿势、挑战经典足球射门轨迹的单页网页游戏。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，例如 `goalkeeper-game`。
2. 将本目录中的全部文件上传到仓库根目录。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. 分支选择 **main**，目录选择 **/(root)**，然后保存。
6. 发布完成后，访问：
   `https://你的GitHub用户名.github.io/goalkeeper-game/`

## 文件说明

- `index.html`：完整游戏，包含界面、样式和逻辑。
- `.nojekyll`：让 GitHub Pages 直接按静态网页发布。
- `README.md`：本说明文件。

游戏不依赖服务器、数据库或第三方运行库，可以直接作为静态网站发布。