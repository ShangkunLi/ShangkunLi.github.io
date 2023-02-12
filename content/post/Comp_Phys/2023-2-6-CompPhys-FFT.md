---
# 常用定义
title: "CompPhys: FFT"
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

这一章节主要介绍傅立叶变换的相关算法

[CompPhys: FFT](/pdf/Comp_Phys/Computational_Physics-FFT-5.pdf)

# 求解问题

## 题目说明

1. $\hat H =-\frac{\hbar^2}{2m}\frac{\partial^2}{\partial x^2} +V(x)$. Periodic potential $V(x)=V(x+a)$.
    Using FFT, find the lowest three eigenvalues of the eigenstates that satisfy $\psi_i=\psi_i(x+1)$

   $U_0=2eV, L_w=0.9nm, L_B=0.1nm, a=1nm$

2. Download the file called sunspots.txt, which contains the observed number of sunspots on the Sun for each month since January 1749.

   Write a program to calculate the Fourier transform of the sunspot data and then make a graph of the magnitude squared $|c_k|^2$ of the Fourier coeﬀicients as a function of k—also called the power spectrum of the sunspot signal. You should see that there is a noticeable peak in the power spectrum at a nonzero value of k. Find the approximate value of k to which the peak corresponds. What is the period of the sine wave with this value of k?

## Documentation

[FFT Documentation](/pdf/Comp_Phys/Assignment_06.pdf)

## Source Code

[FFT Source Code](https://github.com/ShangkunLi/Computational_Physics/tree/main/Assignment%2006)
