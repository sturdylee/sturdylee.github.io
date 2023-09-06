---
title: 基于 Github Pages + Hexo 搭建个人博客
date: 2023-09-05 11:18:42
categories:
    - 天工开物
tags: ['hexo', 'fluid']
---

## 上传博客

 新建文章

> 输入命令：hexo new "文章名称"

预览

> 输入命令（blog目录下使用git）：hexo s

确认无误后生成文件

> 输入命令：hexo g

部署到Github

> 输入命令：hexo d

## 疑难问题

解决 Github port 443: Time out

```
# 取消代理
git config --global --unset http.proxy
git config --global --unset https.proxy

# 查看代理
git config --global --get http.proxy
git config --global --get https.proxy
```

## 参考资料

* **Hexo Docs**：https://hexo.io/zh-cn/docs/
* **Hexo Fluid 用户手册**：https://fluid-dev.github.io/hexo-fluid-docs/
* [白嫖GitHub Pages，轻松搭建个人博客_Hexo_LigaAI_InfoQ写作社区](https://xie.infoq.cn/article/ac51ce1f6e9434779c35cbb6c)
* [hexojs/awesome-hexo: A curated list of awesome things related to Hexo (github.com)](https://github.com/hexojs/awesome-hexo)
* [解决 Github port 443 : Timed out - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/636418854)


