---
# 常用定义
title: "CompPhys: Ordinary Differential Equations"
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

这一章节主要常微分方程的数值求解方法

[CompPhys: Ordinary Differential Equations](/pdf/Comp_Phys/Computational_Physics-ODE-6.pdf)

# 求解问题

## 题目说明

1. Write a code to numerically solves the motion of a simple pendulum using Euler’s method, midpoint method, RK4, Euler-trapezoidal method (implement these methods by yourself). Plot the angle and total energy as a function of time. Explain the results.

2. Write a code to numerically solves radial Schrödinger equation for:

      $$  \left[-\frac{1}{2}\nabla^2+V(r)\right]\psi( r)=E\psi(r), V( r)=V(r)$$

   ​    (1) $V(r)=-\frac{1}{r}$ (hydrogen atom)

   ​    (2) $Z_{ion}=0.4000000, C_1=-14.0093922$

   ​		 $C_2=9.5099073, C_3=-1.7532723, C_4=0.0834586$

   ​        $$ V(r)=-\frac{Z_{ion}}{r}erf\left(\frac{r}{\sqrt{2}r_{loc}}\right)+exp\left[-\frac{1}{2}\left(\frac{r}{r_{loc}}\right)^2\right]$$
   
   ​					$$\times\left[C_1+C_2\left(\frac{r}{r_{loc}}\right)^2+C_3\left(\frac{r}{r_{loc}}\right)^4+C_4\left(\frac{r}{r_{loc}}\right)^6\right]\nonumber $$
   
   ​    Compute and plot the first three eigenstates.


## Documentation

[Ordinary Differential Equations Documentation](/pdf/Comp_Phys/Assignment_07.pdf)

## Source Code

[Ordinary Differential Equations Source Code](https://github.com/ShangkunLi/Computational_Physics/tree/main/Assignment%2007)