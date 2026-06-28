# 唐心如个人主页

这是一个适合直接发布到 GitHub Pages 的静态个人主页。页面不需要构建工具，上传到 GitHub 后即可通过 `github.io` 访问。

## 文件结构

- `index.html`：主页内容
- `assets/styles.css`：页面样式
- `assets/avatar.jpg`：头像照片
- `.nojekyll`：让 GitHub Pages 按普通静态站点发布

## 发布到 GitHub Pages

### 方式一：发布到 `username.github.io`

1. 在 GitHub 创建仓库，仓库名使用你的 GitHub 用户名加 `.github.io`，例如 `yourname.github.io`。
2. 将本目录下的所有文件上传到仓库根目录。
3. 推送到 `main` 分支后，访问 `https://yourname.github.io`。

### 方式二：发布到普通仓库

1. 在 GitHub 创建任意仓库，例如 `personal-homepage`。
2. 将本目录下的所有文件上传到仓库根目录。
3. 打开仓库的 `Settings` -> `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/root`。
5. 保存后访问 GitHub 给出的 Pages 地址。

## 本地预览

直接双击 `index.html` 即可预览。也可以在本目录运行：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 可继续补充的内容

- 已公开论文标题和链接
- GitHub、Google Scholar、个人实验室主页等外链
- 可公开的开源项目链接
- 个人 CV PDF 下载链接
