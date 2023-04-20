---
# 常用定义
title: "Hugo-Jane主题个性化记录"
date: 2023-4-21    # 创建时间
lastmod: 2023-04-21 # 最后修改时间
draft: false                       # 是否是草稿？
tags: ["网站", "开发"]  # 标签
categories: []     # 分类
author: "李尚坤"                  # 作者

# 用户自定义
# 你可以选择 关闭(false) 或者 打开(true) 以下选项
comment: false   # 关闭评论
toc: false       # 关闭文章目录
# 你同样可以自定义文章的版权规则
contentCopyright: '<a rel="license noopener" href="https://creativecommons.org/licenses/by-nc-nd/4.0/" target="_blank">CC BY-NC-ND 4.0</a>'
reward: false	 # 关闭打赏
mathjax: true    # 打开 mathjax
---

本博客的主要目的是用于记录jane主题的一些个性化需求的更改，以防后续查询

# 个性化字体

打开`themes/jane/assets/sass/_variables.scss`文件：

在Global部分，设置全文章的字体。如下设置后在macOS中，中英文都能更换为目标字体。在Windows中，只有英文能够更换为Times New Roman字体

```scss
// Default line height for all type. `$global-lineheight` is 24px while `$global-font-size` is 16px.
$global-lineheight: 1.5 !default;

// Font family of the site.
$global-font-family: 'Times New Roman','Source Sans Pro', 'Helvetica Neue', Arial, sans-serif !default;

// Serif font family of the site.
$global-serif-font-family: 'Times New Roman',Athelas, STHeiti, Microsoft Yahei, serif !default;
```

在Header部分，设置如下的字体，可以将Shangkun's Blog在各种浏览器及系统中均设为Times New Roman字体

```scss
// Font family of the logo.
$logo-font-family:'Times New Roman',LiSu, sans-serif !default;
```

# 个性化排版

打开`/themes/jane/assets/sass/_partial/_post/_content.scss`文件：

在如下代码块中加入`text-align`内容，即可设置对齐的相关参数

```scss
 p {
    //font-size: 1em;
    text-align: justify;
  }
```

