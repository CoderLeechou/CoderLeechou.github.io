---
title: "Hugo 博客搭建指南"
date: 2026-05-06
description: "从零开始搭建 Hugo 博客的完整指南"
tags: ["Hugo", "教程"]
categories: ["技术"]
---

## 环境准备

在开始之前，请确保你的系统已安装以下工具：

- **Git** — 版本管理
- **Hugo Extended** — 静态站点生成器

## 安装 Hugo

### Linux

从 [Hugo Releases](https://github.com/gohugoio/hugo/releases) 下载对应平台的二进制文件。

### macOS

```bash
brew install hugo
```

## 创建站点

```bash
hugo new site my-blog
cd my-blog
```

## 安装主题

```bash
git clone https://github.com/CaiJimmy/hugo-theme-stack.git themes/stack
```

然后在 `hugo.toml` 中设置 `theme = "stack"`。

## 写作

Hugo 使用 Markdown 编写内容，支持以下特性：

- **代码高亮** — 自动语法着色
- **目录生成** — 自动生成文章目录
- **短代码** — 扩展 Markdown 功能
- **图片处理** — 自动响应式图片

> 提示：使用 `hugo server -D` 命令可以在本地预览包含草稿的站点。
