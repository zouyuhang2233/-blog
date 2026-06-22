# 我心逝 — 博客使用指南

## 网址

线上：**https://zouyuhang2233.github.io/-blog**
本地预览：http://localhost:4000

---

## 写文章

在 source/_posts/ 里新建 .md 文件，格式如下：

```markdown
---
title: 文章标题
date: 2026-06-22 10:30:00
tags: [标签1, 标签2]
---

## 小标题

正文内容，支持 Markdown。
```

保存后就写好了。

---

## 在 VS Code 更新博客

写完文章后，在 VS Code 按 **Ctrl + `** 打开终端，输入：

```bash
npx hexo clean && npx hexo deploy
```

等它跑完，打开 https://zouyuhang2233.github.io/-blog 就能看到更新了。

---

## 本地预览

```bash
npx hexo server
```

浏览器打开 http://localhost:4000，关掉按 Ctrl+C。

---

## 备份源码（可选）

```bash
git add -A
git commit -m "更新"
git push origin source
```

不跑也行，网站不受影响。

---

## 项目结构

| 文件/文件夹 | 作用 |
|-----------|------|
| source/_posts/ | 文章 |
| source/about/ | 关于我 |
| source/photos/ | 照片 |
| source/css/editorial.css | 自定义样式 |
| _config.yml | 全局配置 |
| _config.butterfly.yml | 主题配置 |
