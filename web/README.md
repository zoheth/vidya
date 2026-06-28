# web

vidyā 的静态站点。用 [Astro](https://astro.build) 把 `canon/` 里的 Markdown 渲染成页面。

内容仍然写在仓库根目录的 `canon/` 里，本目录只承载呈现。

## 本地开发

```sh
cd web
npm install
npm run dev      # http://localhost:4321/vidya/
```

## 生产构建

```sh
npm run build    # 输出到 web/dist/
npm run preview  # 本地预览构建结果
```

## 部署

推送到 `master` 后由 `.github/workflows/deploy.yml` 自动构建并发布到 GitHub Pages。

首次启用：在 GitHub 仓库 Settings → Pages 把 Source 设为 "GitHub Actions"。

部署地址：`https://zoheth.github.io/vidya/`

## 配置要点

- `astro.config.mjs`：`base: '/vidya'` 对应 GitHub Pages 的子路径。若改用自定义域名，把 `base` 改成 `'/'`。
- `src/content.config.ts`：定义两个内容集合——`canon`（所有论文，按 `canon/<category>/<slug>.md` 路由）和 `pages`（顶层 README 与 canon 索引）。
- `src/lib/remark-rewrite-canon-links.mjs`：把 Markdown 里的 `*.md` 相对链接重写为站内干净 URL。
- `src/styles/global.css`：极简、衬线为主、中文排版友好。颜色由系统深浅色偏好自动切换。
