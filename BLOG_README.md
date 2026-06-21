# 我心逝 - 博客项目

## 基本信息

| 项目 | 内容 |
|------|------|
| 博客名 | 我心逝 |
| 作者 | 我心逝 |
| 框架 | Hexo 5.5.5 |
| 主题 | Butterfly 5.5.5 |
| 语言 | 中文 |
| GitHub | https://github.com/zouyuhang2233 |
| 本地地址 | http://localhost:4000 |

## 日常操作

### 启动服务器
```bash
cd Desktop/my-blog
npx hexo server
```
浏览器打开 http://localhost:4000 查看，Ctrl+C 停止。

### 添加新文章
```bash
npx hexo new post "文章标题"
```
文件生成在 `source/_posts/` 下，用 Markdown 写。保存后浏览器自动刷新。

顶部 frontmatter 可以加 cover 头图：
```markdown
---
title: 文章标题
date: 2026-06-21
tags: [标签1, 标签2]
cover: https://图片地址.jpg
---
```

### 添加新页面
```bash
npx hexo new page 页面名
```
文件在 `source/页面名/index.md`。

## 重要文件

| 文件 | 作用 |
|------|------|
| `_config.yml` | 博客全局配置（标题、作者、语言等） |
| `themes/butterfly/_config.yml` | 主题配置（外观、社交链接、公告等） |
| `source/_posts/` | 所有文章 |
| `source/about/index.md` | 关于我页面 |

## 注意事项

- 暂不部署到 GitHub Pages，仅本地查看
- 暂不加评论功能
- 风格：杂志感，简洁阅读风
- 以后想改外观、加功能，修改 themes/butterfly/_config.yml
