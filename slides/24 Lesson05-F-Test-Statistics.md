---
title: F-Test Statistics
template: default
---

We have seen that
$$
\frac{n-p}{\sigma^2}\hat{\sigma}^2=\frac{1}{\sigma^2}\| Y- D\hat{\beta}\|^2_2 \sim \chi^2_{n-p}
$$
but the true variance $\sigma^2$ is unknown.

This leads to a new test statistic formed as a ratio of two **independent** variance estimates.

Assume two **nested** hypotheses:

$$
H_R \subset H_F
$$
with design matrices $D_R$ and $D_F$, and dimensions $p_R < p_F$, such that

$$
\operatorname{span}(D_R) \subset \operatorname{span}(D_F)
$$

Under $H_R$, the following statistic is $F$-distributed:

$$
\frac{\big(\| Y - D_R \hat{\beta}_R \|^2 - \| Y - D_F \hat{\beta}_F \|^2\big)/(p_F - p_R)}
{\| Y - D_F \hat{\beta}_F \|^2/(n - p_F)}
\sim F_{p_F - p_R,\, n - p_F}
$$
