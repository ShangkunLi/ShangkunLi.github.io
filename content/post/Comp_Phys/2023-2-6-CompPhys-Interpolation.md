---
# 常用定义
title: "CompPhys: Interpolation"
date: 2023-2-6    # 创建时间
lastmod: 2023-01-20 # 最后修改时间
draft: false                       # 是否是草稿？
tags: ["Python", "C/C++", "开发"]  # 标签
categories: ["Computational Physics"]     # 分类
author: "李尚坤"                  # 作者

# 用户自定义
# 你可以选择 关闭(false) 或者 打开(true) 以下选项
comment: false   # 关闭评论
toc: true       # 关闭文章目录
# 你同样可以自定义文章的版权规则
contentCopyright: '<a rel="license noopener" href="https://creativecommons.org/licenses/by-nc-nd/4.0/" target="_blank">CC BY-NC-ND 4.0</a>'
reward: false	 # 关闭打赏
mathjax: true    # 打开 mathjax


---

# 介绍

这一章节主要介绍插值的相关算法，如牛顿插值法，样条插值法等

[Computational Physics: Interpolation](/pdf/Comp_Phys/Computational_Physics-Interpolation-3.pdf)

# 求解问题

## 题目说明

1. Newton interpolation of:

   (i) 10 equal spacing points of cos x within $[0, π]$,

   (ii) 10 equal spacing points $\frac{1}{1+25x^2}$ within $[-1,1]$. 

   Compare the results with the cubic spline interpolation.

2. The table below gives the temperature T along a metal rod whose ends are kept at fixed constant temperature. The temperature is a function of the distance x along the rod.

   (1)Compute a least-squares, straight-line fit to these data using$ T (x) = a + bx $

   (2)Compute a least-squares, parabolic-line fit to these data using$ T(x) = a+bx+cx^2$

| x/cm | 1.0  | 2.0  | 3.0  | 4.0  | 5.0  | 6.0  | 7.0  | 8.0  | 9.0  |
| :--: | :--: | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| T/c  | 14.6 | 18.5 | 36.6 | 30.8 | 58.2 | 60.1 | 62.2 | 79.4 | 99.9 |

## Documentation

[Interpolation Documentation](/pdf/Comp_Phys/Assignment_04.pdf)

## Source Code

[Interpolation Source Code](https://github.com/ShangkunLi/Computational_Physics/tree/main/Assignment%2004)