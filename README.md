# 我的博客

基于 [Hugo](https://gohugo.io/) 和 [Stack](https://github.com/CaiJimmy/hugo-theme-stack) 主题搭建的个人博客。

## 本地开发

```bash
# 启动开发服务器 (含草稿预览)
hugo server -D

# 构建生产版本
hugo --minify
```

## 目录结构

- `content/` -- 博客内容 (Markdown 文件)
- `static/` -- 静态资源 (图片、图标等)
- `assets/` -- Hugo 资源文件 (头像等)
- `themes/stack/` -- Stack 主题
- `hugo.yaml` -- 站点配置文件
- `archetypes/` -- 内容模板

## 部署

本站使用 GitHub Actions 自动部署到 GitHub Pages，详见 `.github/workflows/` 目录。
