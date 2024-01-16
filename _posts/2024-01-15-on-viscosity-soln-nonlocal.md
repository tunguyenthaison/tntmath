---
layout: post
title: "On viscosity solution of nonlocal HJB"
author: "tntmanth"
tags: math, 
excerpt_separator: <!--more-->
mathjax: true
date: 2024-01-15
---

<!--more-->

If $Iu \leq f$ in the viscosity sense, and $\varphi\in C^2$ such that

$$
    \varphi(x) = u (x), \qquad \varphi(y) > u(y)\qquad \text{for}\;y\neq x.
$$

We claim that $Iu(x)$ is well-defined in the classical sense, with $Iu(x)\leq f(x)$ classically.

The maximal operator is defined by

$$
\begin{equation*}
    \mathcal{M}^+(f,x) = \sup_{l\in [\partial j]_{\mathcal{K}(\gamma,m)}} l(f) \qquad\text{where}\qquad j(f) = J(f,0).
\end{equation*}
$$

The nonlocal part of $l$ (a linear operator) is given by

$$
\begin{equation*}
    l(f) = \int_{\mathbb{R}^n} \Big(f(y) - f(0) - \mathbf{1}_{B_1}(y) \nabla f(0)\cdot y\Big)\;d\mu(y)
\end{equation*}
$$

where 

$$
\begin{equation*}
    \int_{\mathbb{R}^n} |y|^{1+\gamma}\;d\mu(y) \leq C. 
\end{equation*}
$$

> **Goal** If $u$ is $C^{1,1}(x)$ such that $Iu\leq f$ in viscosity sense, then it must be true in classical sense at the point $x$.