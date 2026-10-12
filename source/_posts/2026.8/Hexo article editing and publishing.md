---
title: Hexo-butterfly文章编辑发布指南
date: 2026-08-16 10:00:00
tags:
  - Hexo
  - Butterfly
  - 教程
categories:
  - 建站日志
# 我为你默认调用了之前配置的故宫图片作为这篇文章的首图，你也可以换成其他的
cover: /img/quanqiu.png 
---

历经一番折腾，从修改基础配置、调整搜索框，到美化字体和背景，我的个人博客终于搭建初具规模啦！

这是我的第一篇文章。为了方便以后自己写博客，也为了给同样使用 Hexo + Butterfly 主题的小伙伴提供参考，我整理了这篇日常文章编辑与发布的指南。

<!-- more -->

## 一、 认识 Front-matter (文章抬头)

在每篇 Markdown 文章的最顶部，都有由两行 `---` 包围的部分，这被称为 Front-matter。它告诉了 Hexo 这篇文章的核心信息。

常见的基础配置如下：

```yaml
title: 文章的标题
date: 2026-08-16 10:00:00 # 发布时间
tags: 
  - 标签1
  - 标签2
categories: 
  - 分类名称
cover: /img/xxx.jpg # 文章的主图/封面图