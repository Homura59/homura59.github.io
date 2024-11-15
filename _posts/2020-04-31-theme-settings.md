---
title: 如何使用 simple 主题
---

Simple 是针对移动端开发的响应式 Jekyll 主题，兼具云笔记和博客功能，特性包括但不限于

1. 在线编辑、新建、发布文章[^1]
2. 支持 GitHub 官方 markdown 语法[^2]
3. 使用 LaTex 语法编辑数学公式[^3]
4. 可在文章中使用流程图[^4]
5. 在文章中嵌入 B 站、Youtube 视频[^5]
6. gitalk 评论系统[^6]
8. 原生 JS 实现站内全局搜索
9. CDN 加速，国内外访问都很快

如果你注重博客内容，那么这款沉浸式主题绝对适合你。

1. 目录
{:toc}

## 快速搭建

你可以选择直接在 github 上操作，或者在本地上修改主题再发布到自己的仓库里。

### 线上操作

线上操作只需要 5 分钟。

1. fork [本仓库](https://github.com/Homura59/homura59.github.io)。
2. 修改仓库名为 `username.github.io`，`username` 是你的 GitHub 账户名，然后创建 `master` 分支并设置为默认分支。
3. 修改 `_config.yml` 文件中的相应个人信息。

完成上面三步后，浏览器访问 `https://username.github.io` 查看属于你的网站。(有问题下方留言)

### 本地运行

1. 本地安装 Jekyll 
2. clone 主题到本地
3. 进入主题根目录后运行 `jekyll serve`

浏览器中输入 `http://localhost:4000` 预览。（有问题下方留言）

## 网站样式设置

通过修改 `_sass/_variables.scss` 文件，可以实现该主题的高度定制化，包括但不限于

1. 通过 `--font` 修改字体
2. 通过 `--body-bg` 修改网页背景的颜色
3. 通过 `--heading-color` 修改标题的颜色
5. 通过 `--link-color` 修改链接的颜色
