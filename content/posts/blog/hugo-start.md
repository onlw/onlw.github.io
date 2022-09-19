---
title: "Hugo Start"
date: 2022-09-18T21:46:38+08:00
draft: false
---

## 安装hugo （mac）

```bash
brew install hugo
```
## 初始化博客
```bash
hugo new my-blog
```

## 安装主题
```bash
cd my-blog
git init
git submodule add https://github.com/miiiku/hugo-theme-kagome.git ./themes/kagome
cp -rf themes/kagome/exampleSite/* ./

```

## 运行
```bash
hugo start
```

## 接入 github-pages
