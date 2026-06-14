# Thomas 个人主页

这是一个按照 `用户名.github.io` 方法搭建的静态个人主页。仓库根目录放 `index.html`，GitHub Pages 会把它作为首页发布。

## 怎么修改

- 在 `index.html` 里替换姓名、介绍、作品和联系方式。
- 在 `styles.css` 里调整颜色、间距和版式。
- 如果要换头像，替换 `assets/profile-card.svg`，并保持文件名不变，或者同步修改 `index.html` 里的图片路径。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，名字写成 `你的GitHub用户名.github.io`。
2. 上传本文件夹里的 `index.html`、`styles.css`、`assets/` 和 `README.md`。
3. 如果 GitHub 没有自动发布，打开仓库的 Settings → Pages。
4. Source 选择 `Deploy from a branch`，Branch 选择 `main` 和 `/root`。
5. 保存后等待 GitHub 生成网址。

如果仓库名是 `xuejiyou.github.io`，主页地址通常就是 `https://xuejiyou.github.io/`。
