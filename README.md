# 4B Final Review Helper

这是一个可以直接部署到 GitHub Pages 的静态网页项目。

## 文件

- `index.html`: 网页入口，来自桌面的 `期末复习_完整版核验版.html`
- `.nojekyll`: 让 GitHub Pages 按普通静态文件发布

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，例如 `final-review-helper`。
2. 在本文件夹打开终端，运行：

```powershell
git remote add origin https://github.com/YOUR_USERNAME/final-review-helper.git
git branch -M main
git push -u origin main
```

3. 打开 GitHub 仓库页面，进入 `Settings` -> `Pages`。
4. Source 选择 `Deploy from a branch`，Branch 选择 `main` 和 `/root`，保存。
5. 等待 GitHub Pages 构建完成，网页地址通常是：

```text
https://YOUR_USERNAME.github.io/final-review-helper/
```

如果你安装并登录了 GitHub CLI，可以用：

```powershell
gh repo create final-review-helper --public --source . --remote origin --push
```

然后再到仓库的 `Settings` -> `Pages` 开启发布。
