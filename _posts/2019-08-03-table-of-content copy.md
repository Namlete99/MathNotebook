---
layout: post
title: Test 
date:   2019-08-03 11:07
description: For some big articles you can use table on content
tag: math
math: true
toc: true
share: true
---

# Các phương trình ngắn

The mathematics powered by [**MathJax**](https://www.mathjax.org/):

$$
\begin{equation}
  \sum_{n=1}^\infty 1/n^2 = \frac{\pi^2}{6}
  \label{eq:series}
\end{equation}
$$

We can reference the equation as \eqref{eq:series}.

When \\\(a \ne 0\\\), there are two solutions to $ax^2 + bx + c = 0$ and they are

$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

# Kí hiệu toán học 

\\\(x \in \mathbb{N}\\\)

$x \in \mathbb{N}$

# Các phương trình dài dòng

$$
\begin{equation*}
\begin{aligned}
\det(B) &= \sum_{\sigma \in S_3} \operatorname{sgn}(\sigma) \prod_{k=1}^{3} a_{k, \sigma(k)} \\

\\

&= \left[ \operatorname{sgn}(\sigma_1) a_{1\sigma_1} a_{2\sigma_2} a_{3\sigma_3} \right] + \left[ \operatorname{sgn}(\sigma_2) a_{1\sigma_1} a_{2\sigma_2} a_{3\sigma_3} \right] + \left[ \operatorname{sgn}(\sigma_3) a_{1\sigma_1} a_{2\sigma_2} a_{3\sigma_3} \right] + \left[ \operatorname{sgn}(\sigma_4) a_{1\sigma_1} a_{2\sigma_2} a_{3\sigma_3} \right] + \left[ \operatorname{sgn}(\sigma_5) a_{1\sigma_1} a_{2\sigma_2} a_{3\sigma_3} \right] + \left[ \operatorname{sgn}(\sigma_6) a_{1\sigma_1} a_{2\sigma_2} a_{3\sigma_3} \right]\\

\\

&= (1.a_{11}.a_{22}.a_{33}) + ((-1).a_{11}.a_{23}.a_{32}) + ((-1).a_{12}.a_{21}.a_{33}) + (1.a_{12}.a_{23}.a_{31}) + (1.a_{13}.a_{21}.a_{32}) + ((-1).a_{13}.a_{22}.a_{31}) \\

\\

&= (a_{11}.a_{22}.a_{33} + a_{12}.a_{23}.a_{31} + a_{13}.a_{21}.a_{32}) - (a_{11}.a_{23}.a_{32} + a_{12}.a_{21}.a_{33} + a_{13}.a_{22}.a_{31})
\end{aligned}
\end{equation*}
$$

trong đó: 

+ \\\(D_{i_{1} \dots i_{k}}^{j_{1} \dots j_{k}}\\\) là định thức của ma trận vuông con cấp k, được xác định bởi các phần tử nằm trên giao của các dòng \\\(i_{1}, \dots , i_{k}\\\) và các cột \\\(j_{1}, \dots, j_{k}\\\).

+ \\\((-1)^{i_{1} + \dots + i_{k} + j_{1} + \dots + j_{k}} \overline{D}_{i_{1} \dots i_{k}}^{j_{1} \dots j_{k}}\\\) là phần bù đại số của \\\(D_{i_{1} \dots i_{k}}^{j_{1} \dots j_{k}} \\\). Với \\\(\overline{D}_{i_{1} \dots i_{k}}^{j_{1} \dots j_{k}}\\\) được gọi là định thức con bù của ma trận vuông cấp \\\(n - k\\\), được xác định bởi các phần tử không nằm trên giao của các dòng \\\(i_{1}, \dots , i_{k}\\\) và các cột \\\(j_{1}, \dots, j_{k}\\\). 

+ \\\((-1)^{i_1 + \dots i_k + j_1 + \dots + j_k} \cdot \overline{D}_{i_1 \dots i_k}^{j_1 \dots j_k}\\\) là phần bù đại số của \\\(D_{i_{1} \dots i_{k}}^{j_{1} \dots j_{k}}\\\). Với \\\(\overline{D}_{i_1 \dots i_k}^{j_1 \dots j_k}\\\) được gọi là định thức con bù của ma trận vuông cấp \\\(n - k\\\), được xác định bởi các phần tử không nằm trên giao của các dòng \\\(i_{1}, \dots , i_{k}\\\) và các cột \\\(j_{1}, \dots, j_{k}\\\).