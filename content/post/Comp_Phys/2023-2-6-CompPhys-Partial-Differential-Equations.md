---
# 常用定义
title: "CompPhys: Partial Differential Equations"
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

[CompPhys: Partial Differential Equations](/pdf/Comp_Phys/Computational_Physics-PDE-7.pdf)

# 求解问题

## 题目说明

1. Consider the Poisson equation:

   ​        $$ \nabla^2\phi(x,y)=-\rho (x,y) / \epsilon_0 $$

   from electrostatics on a rectangular geometry with $x\in[0,L_x]$ and $y\in[0,L_y]$. Write a program that solves this equation using the relaxation method. Test your program with:

   (a) $\rho(x,y)=0,\ \phi(0,y)=\phi(L_x,y)=\phi(x,0)=0,\ \phi(x,L_y)=1V,\ L_x=1m.\ L_y=1.5m$

   (b) $\rho(x,y)/\epsilon_0=1V/m^2,\ \phi(0,y)=\phi(L_x,y)=\phi(x,0)=\phi(x,L_y)=0,\ L_x=1m.\ L_y=1m$

2. Solve the time-dependent Schrodinger equation using both the Crank–Nicolson scheme and stable explicit scheme. Consider the one-dimensional case and test it by applying it to the problem of a square well with a Gaussian initial state coming in from the left.

   Gaussian initial state:$\Psi(x,0)=\sqrt{\frac{1}{\pi}}exp(ik_0x-\frac{(x-\xi)^2}{2})$

3. Prove the stability condition of the explicit scheme of the 1D wave equation by performing Von Neumann stability analysis:

   $$\frac{\partial^2u}{\partial t^2}=c^2\frac{\partial^2u}{\partial x^2}$$

   If $\frac{c\Delta t}{\Delta x}\le1$, the explicit scheme is stable.

## Documentation

[Partial Differential Equations Documentation](/pdf/Comp_Phys/Assignment_08.pdf)

## Source Code

[Partial Differential Equations Source Code](https://github.com/ShangkunLi/Computational_Physics/tree/main/Assignment%2008)