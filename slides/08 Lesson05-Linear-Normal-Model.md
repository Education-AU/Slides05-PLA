---
title: Linear Normal Models
template: default
---

Using properties of the exponential function, we can rewrite the joint density as
$$
f(y_1, y_2, \dots, y_n) = \left( \frac{1}{\sigma \sqrt{2\pi}} \right)^n
\exp\left( -\frac{1}{2\sigma^2} \sum_{i=1}^n (y_i - \mu_i)^2 \right)
$$

Note that the exponent contains the $L_2$-norm of the difference of vector coordinates $y=(y_1,y_2,\dots y_n)$ and $\mu=(\mu_1,\mu_2,\dots \mu_n)$

$$
f(y) = \left( \frac{1}{\sigma \sqrt{2\pi}} \right)^n
\exp\left( -\frac{1}{2\sigma^2} \| y - \mu\|^2 \right)
$$

If we assume that $\mu$ lies in some subspace $W \subset \mathbb{R}^n$, we obtain the basis for the **general linear normal model**.
