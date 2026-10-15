# 公共安全垂直大模型 + 警务行业智能体 — 软件设计方案

本仓库为 GitHub Pages 静态文档站点，用于发布《公共安全垂直大模型 + 警务行业智能体软件设计方案》。

## 上线前必改

- 站点标题与描述位于 `index.html` 的 `<title>` 与封面区域
- 如需自定义域名，在仓库 Settings → Pages 中配置
- 如有联系方式、版权信息，替换 README 与页脚占位内容

## 本地预览

```bash
cd site
python3 -m http.server 8138
# 浏览器打开 http://127.0.0.1:8138
```

## 部署

- 仓库启用 GitHub Pages 后，访问地址：https://phoenix1983413.github.io/
- 如需绑定自定义域名，在仓库 Settings → Pages 中配置

## 文档结构

- `index.html` — 完整设计文档（含封面、目录、12 章正文）
- `404.html` — 自定义错误页
- `robots.txt` / `sitemap.xml` — 搜索引擎收录配置
- `.nojekyll` — 确保静态资源正常发布
