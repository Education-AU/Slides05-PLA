---
title: Linear Normal Models
template: default
---
Consider a series of measurements $y_1, y_2, \dots, y_n$ modeled as outcomes of $n$ **independent** random variables $Y_1, Y_2, \dots, Y_n$.

Assume that each $Y_i$ is **normally distributed** with mean $\mu_i$, and that all $Y_i$ share the same variance $\sigma^2$:
$$
Y_i \sim \mathcal{N}(\mu_i, \sigma^2)
$$

The density of each $Y_i$ is
$$
f(y_i) = \frac{1}{\sigma \sqrt{2\pi}} \exp\left(-\frac{(y_i - \mu_i)^2}{2\sigma^2}\right)
$$

Since the variables are independent, the joint density is
$$
f(y_1, \dots, y_n) = \prod_{i=1}^n \frac{1}{\sigma \sqrt{2\pi}} \exp\left(-\frac{(y_i - \mu_i)^2}{2\sigma^2}\right)
$$
