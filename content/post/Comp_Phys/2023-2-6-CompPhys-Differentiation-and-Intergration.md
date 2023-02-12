---
# 常用定义
title: "CompPhys: Differentiation and Intergration"
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

这一章节主要介绍数值微分与积分的方法

[Computational Physics: Differentiation and Intergration](/pdf/Comp_Phys/Computational_Physics-differentiation-integration-4.pdf)

# 求解问题

## 题目说明

1. Compute the derivative of $f(x) = sinx$ at $x = π/3$ using the Richardson extrap- olation algorithm. Start with h = 1 and find the number of rows in the Richardson table required to estimate the derivative with six significant decimal digits. Output the Richardson table.

2. Radial wave function of the 3s orbital is:

   $R_{3s} = \frac{1}{9√3} ×(6−6ρ+ρ^2)×Z^{3/2}×e^{-\rho/2}$

   · r = radius expressed in atomic units (1 Bohr radius = 52.9 pm)

   · e = 2.71828 approximately

   · Z = effective nuclear charge for that orbital in that atom

   · ρ = 2Zr/n where n is the principal quantum number (3 for the 3s orbital)

   Compute $∫_0^{40}|R_{3s}|^2r^2dr $for Si atom (Z = 14) with Simpson’s rule using two different radial grids:

   (1)Equalspacinggrids: $r[i]=(i−1)h$  ;  $i=1,···,N$ (trydifferentN)
   
   (2) A nonuniform integration grid, more finely spaced at small r than at large r:

   $r[i] = r_0(e^{t[i]} − 1)$; $t[i] = (i − 1)h$;$ i = 1,· · · , N$ (One typically choose$ r_0 = 0.0005$ a.u., try different N)

   (3) Find out which one is more eﬀicient, and discuss the reason.

## Documentation

[Differentiation and Intergration Documentation](/pdf/Comp_Phys/Assignment_05.pdf)

## Source Code

[Differentiation and Intergration Source Code](https://github.com/ShangkunLi/Computational_Physics/tree/main/Assignment%2005)