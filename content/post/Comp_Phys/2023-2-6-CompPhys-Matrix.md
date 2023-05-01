---
# 常用定义
title: "CompPhys: Matrix"
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
katex: true

---

# 介绍

这一章节主要介绍矩阵的相关处理，消元，矩阵分解，特征值问题等

[Computational Physics: Matrix](/pdf/Comp_Phys/Computational_Physics-matrix-2.pdf)

# 求解问题

## 题目说明

1. Prove that the time complexity of the Gaussian elimination algorithm is $$O(N^3)$$

2. Write a general code to transform a n×m matrix into the REDUCED ROW ECHE-

    LON FORM, and use the code to obtain the RREF of the following matrix.

3. Solve the 1D Schrodinger equation with the potential 

     (i) $$V (x) = x^2$$

     (ii) $$V (x) = x^4 − x^2 $$with the variational approach using a Gaussian basis (either fixed widths or fixed centers). Consider the three lowest energy eigenstates.

## Documentation

[Matrix Documentation](/pdf/Comp_Phys/Assignment_03.pdf)

## Source Code

[Matrix Source Code](https://github.com/ShangkunLi/Computational_Physics/tree/main/Assignment%2003)