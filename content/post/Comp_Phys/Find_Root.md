---
# 常用定义
title: "CompPhys: Find Root"
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

这一章节主要介绍寻找方程根与函数极小值的方法（如梯度下降法）

[Computational Physics: Find Root](/pdf/Comp_Phys/Computational_Physics-find-root-1.pdf)

# 求解问题

## 题目说明

1. 求解实系数方程$$𝑎𝑥^2+𝑏𝑥+𝑐+0$$的解。要求:系数𝑎, 𝑏, 𝑐为程序执行时键盘输入，𝑎, 𝑏, 𝑐为任意实数，所有的解均输出到屏幕。
2. 24 点游戏是儿时玩的主要益智类游戏之一，玩法为:从一副扑克中抽取 4 张牌，对 4 张牌使用加减乘除中的任何方法，使计算结果为 24。例如， 2,3,4,6，通过(((4+6)-2)*3) =24，最快算出24者胜。请 采用 Fortran90 编程求解 24 点游戏的解。
3. Sketch the function $$𝑥^2−5𝑥+3=0$$:
    (1) Determine the two positive roots to 4 decimal places using the bisection method.
    (2) Take the two roots that you found in the previous question (accurate to 4 decimals) and “polish them up” to 14 decimal places using the Newton-Raphson method.
    (3) Determine the two positive roots to 14 decimal places using the hybrid method.
4. Search for the minimum of the function 𝑔(𝑥, 𝑦) = sin(𝑥 + 𝑦) + cos (𝑥 + 2𝑦) in the whole place
5. Determine 𝑚(𝑡) the reduced magnetization as a function of reduced temperature for simple materials. $$𝑚(𝑡) = 𝑡𝑎𝑛h(𝑚(𝑡)/𝑡)$$
    For a given 𝑡, solve 𝑚, plot 𝑚 as a function of 𝑡.

## Documentation

[Find Root Documentation1](/pdf/Comp_Phys/Assignment_01.pdf)

[Find Root Documentation1](/pdf/Comp_Phys/Assignment_02.pdf)

## Source Code

[Find Root Source Code1](https://github.com/ShangkunLi/Computational_Physics/tree/main/Assignment%2001)

[Find Root Source Code1](https://github.com/ShangkunLi/Computational_Physics/tree/main/Assignment%2002)