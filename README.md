# 张宇 · 游戏开发作品集

GitHub Pages 个人主页 —— UE5 + GAS 毕业设计《苍穹-离界》、手写 Win32 的 2D 格斗游戏《纸狼》、
UE5 第三人称动作游戏、俯视角 Roguelike 原型与 C++ 文字策略游戏《宝可梦世界》。

**在线访问：** https://zhangb0lu0.github.io/ZhangBoluo/

## 特点

- **纯静态**：单个 `index.html`，内联 CSS / JS，无框架、无构建步骤
- **图片本地化**：全部转为 WebP，缩略图与全尺寸分离，`loading="lazy"`（约 8 MB）
- **自建灯箱**：键盘 ← → / 滚轮缩放 / 拖拽 / 移动端滑动，同项目内前后切换
- **响应式**：1440 / 768 / 500 / 390 px 逐档核对，含 `prefers-reduced-motion` 与打印样式
- **可访问性**：语义化标签、`aria-*`、可见焦点、灯箱焦点回收、无 JS 时内容仍可见

## 部署

仓库已配置 GitHub Actions（`.github/workflows/static.yml`），推送 `main` 后自动发布整仓库：

```bash
git add index.html assets
git commit -m "feat: redesign portfolio homepage"
git push
```

## 目录

```
index.html                 作品集主页
assets/img/thesis/         毕业设计截图（webp + 缩略图）
assets/img/pic/            其余项目截图
assets/resume-zhangyu.pdf  简历 PDF
index-legacy-2025.html     旧版首页（备份）
```

## 本地预览

双击 `index.html`，或：

```bash
python -m http.server 8080
```

