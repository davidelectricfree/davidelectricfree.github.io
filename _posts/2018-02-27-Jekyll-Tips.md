---
title: Jekyll 技巧相关
time: 2018.02.27 21:08:32
layout: post
tags:
- Jekyll
- Github
- 中文
excerpt: 没想到第一次接触 Github 是用它给自己搭一个博客，总的来说，GitHub + jekyll 都是我比较陌生的，在本文中，零零碎碎记录一些在搭博客过程中遇到的一些小问题。
---

没想到第一次接触 Github 是用它给自己搭一个博客，总的来说，GitHub + jekyll 都是我比较陌生的，在本文中，零零碎碎记录一些在搭博客过程中遇到一些小问题。

对于我这个本职工作和前端八竿子打不着关系的人来说，在使用 GitHub 和 Jekyll 确实遇到了不少问题，过程可以说是相当艰辛了。在写这篇文章对部分问题进行回顾时，自己都有种被自己蠢哭的赶脚 XD 。

Anyway 还是对问题进行忠实记录，也算是对花费了这么多时间的自己一个答复吧。

1 GitHub Pages 及在使用 GitHub Pages 对博客进行搭建时，期间，对域名购买、域名解析、域名分级、CNAME 等不少知识有所疑惑，零零碎碎查询了不少资料；现贴出如下：

　　a. [一步步在GitHub上创建博客主页(3)]({{ site.url }}http://www.pchou.info/ssgithubPage/2013-01-05-build-github-blog-page-03.html)

2 在 Markdown 下实现首行缩进

　　方式1：可将输入法切换到全角模式，在需要输入的地方输入两个空格即可。

3 修改完后，使用 Ruby Command terminer 进入到 Blog 所在的文件夹中，jekyll serve --safe --watch，在[网页]({{ site.url }}http://localhost:4000/index.html) 中可在本地看到编译结果。
