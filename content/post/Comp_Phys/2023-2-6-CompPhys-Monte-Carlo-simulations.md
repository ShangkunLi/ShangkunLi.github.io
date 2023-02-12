---
# 常用定义
title: "CompPhys: Monte Carlo simulations"
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

这一章节主要偏微分方程的数值求解方法

[CompPhys: Monte Carlo simulations](/pdf/Comp_Phys/Computational_Physics-MC-8.pdf)

# 求解问题

## 题目说明

1. The interior of a $d$-dimensional hypersphere of unit radius is defined by the condition $x_1^2+x_2^2+\dots+x_d^2\le1$. Write a program that finds the volume of a hypersphere using a Monte Carlo method. Test your program for $d=2$ and $d=3$ and then calculate the volume for $d=4$ and $d=5$, compare your results with the exact results. 

2. Write a MC code for a 3D Face-Centered Cubic lattice using the Heisenberg spin model (adopt periodic boundary condition). Estimate the ferromagnetic Curie temperature. 

   ​        $$H=-J \sum\limits_{<i,j>_{NN}}\vec{S_i}\cdot\vec{S_j},\ J=1,\ |\vec{S_i}|=1$$

## Documentation

[Monte Carlo simulations Documentation](/pdf/Comp_Phys/Assignment_09.pdf)

## Source Code

[Monte Carlo simulations Source Code](https://github.com/ShangkunLi/Computational_Physics/tree/main/Assignment%2009)