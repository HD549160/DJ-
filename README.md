# DJ Personal Collection Museum

一个依据 PRD 制作的黑金风格数字私人收藏博物馆。当前内容均为明确标注的演示数据，不代表 DJ 的真实藏品。

## 本地预览

在项目目录运行任意静态服务器，例如：

```bash
npx serve dist
```

## 内容替换

- 演示藏品、艺术家、展览和日志集中在 `dist/app.js` 顶部的数据区。
- 页面设计集中在 `dist/styles.css`。
- 当前演示作品图由本地 SVG 数据生成，不依赖第三方图片服务。替换 `coverImage` / `images` 时建议使用作品原图并保留原始比例。
- 联系邮箱与社交账号未提供，因此站内不会显示虚假联系方式。

## 部署

`dist/` 是完整静态输出，可部署到 GitHub Pages、Cloudflare Pages、Netlify、Vercel 或任何静态主机。

### GitHub Pages

1. 把整个项目上传到 GitHub 仓库的 `main` 分支。
2. 打开仓库 `Settings → Pages`，将 Source 设为 `GitHub Actions`。
3. 项目自带 `.github/workflows/pages.yml`，推送后会自动发布。
4. 发布地址通常为 `https://你的用户名.github.io/仓库名/`。站点已自动兼容 GitHub Pages 的仓库子路径。

