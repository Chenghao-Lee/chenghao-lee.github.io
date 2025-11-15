# ChenghaoLee · 外贸增长官网

基于 CSS3 3D 翻转效果打造的单页外贸官网，包含主页、关于、翻转名片、解决方案以及联系模块，适合直接部署到 GitHub Pages。

## Structure

```
index.html         -> main page
css/style.css      -> global styles and card animation
img/               -> background images used on project cards
```

## 本地预览

```powershell
cd e:\Pan
npx serve .
```

在浏览器里打开 `http://localhost:3000`（或终端输出的端口）即可查看 3D 翻转动画与移动端适配效果。

## 部署到 GitHub Pages

1. 新建仓库并提交本目录所有文件。
2. 在仓库 **Settings → Pages** 中选择 `main` 分支与 `/ (root)` 路径。
3. 等待绿色对勾后访问 `https://<username>.github.io/<repo>/`。

## 可定制点

- 替换 `img/me.jpg` 与 `img/*.png` 以匹配个人照片和案例封面。
- 如需不同服务场景，只需调整 `index.html` 中项目卡片的文案与链接。
- 颜色、光栅背景和动效集中在 `css/style.css`，可通过修改 `:root` 变量和 `.grid-overlay` 渐变获得不同的科技感主题。
