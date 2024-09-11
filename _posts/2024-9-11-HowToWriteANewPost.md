---
title: 如何写一篇文章并上传
categories: [blog,post]
tags: [blog,post]
author: Zpekii
pin: true
---

# 文章编写与上传

## 如何写一篇文章

**主题教程:**[Writing a New Post | Chirpy (cotes.page)](https://chirpy.cotes.page/posts/write-a-new-post/)

### 创建文章Markdown文件

- 文件名格式: 时间-文章标题 `YYYY-MM-DD-Tiltle`

### 编写前言

- 格式如下:

  - ```yaml
    ---
    title: TITLE # 文章标题
    categories: [TOP_CATEGORIE, SUB_CATEGORIE] # 文章分类，默认第一个为主分类，后面的为子分类，
    tags: [TAG]     # 标签名需要英文小写，各标签平行，可以同时有多个标签 
    author: <author_id> # _data/authors.yaml 下存在的作者id
    description: example # 文章简要描述
    comments: true # 默认开启文章评论，若要关闭则填写false
    ---
    ```

    

### 使用Markdown语法编写正文

### 图片引用(如果需要)

- 将图片路径改为项目路径,保存到`assets/img/`下
- 图片语法由`markdown`改为`html`

## 如何上传文章

### 在本地通过git推送至远程仓库

- 将写好的文章markdown文件移动到仓库项目文件下(需要提前clone: `git clone https://github.com/zhGZHUCST2023/zhgzhucst2023.github.io.git`)的 `_post`下
- 然后在本地提交，接着推送到远程仓库即可

**注意：** 提交信息可能需要按照 `commitlint`规范进行编写，上传文章统一格式如下:

- ```
  docs: upload post by {Author} # 必须要有 'docs: '
  ```

  

