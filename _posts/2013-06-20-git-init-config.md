---
layout: post
title: Git 初始化配置
---

# {{ page.title }}

## username

```shell
    git config --global user.name "Your Name"
```

## email

```shell
    git config --global user.email "your@name.com"
```

## 后悔药

如果你在提交(commit)了之后, 才发现没有先配置用户与邮箱?

1. 用上面的命令设置

2. 运行下一条命令

```shell
    git commit --amend --author "Your Name <your@name.com>"
```
