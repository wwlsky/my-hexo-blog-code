---
title: Hexo 使用
date: 2016-06-10 14:55:23
categories: 
 - 博客系统
tags:
---

> hexo 部署到 github

## 修改配置
```yml
deploy:
  type: git
  repo: <repository url>    # 库（Repository）地址
  branch: [branch]          # 分支名称
```

## 发布命令流程
```bash
hexo g  # 生成新的静态文件
hexo d  # 发布到GitHub
```

[# 官方文档](https://hexo.io/zh-cn/docs/)
