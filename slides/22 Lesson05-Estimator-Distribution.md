---
title: Distribution of Estimator  σ̂²
template: default
---

The estimator $\hat{\sigma}^2$ is not normally distributed. Instead, the scaled version

$$
\frac{n-p}{\sigma^2} \, \hat{\sigma}^2 = \frac{1}{\sigma^2} \| Y - D \hat{\beta} \|^2 \sim \chi^2_{n-p}
$$

follows a $\chi^2$ distribution with $n-p$ degrees of freedom.

<div class="center">

<img src="./assets/chisquare5.png" alt="Chi squared distribution" width="30%">

</div>

From the distributions of these estimators, we can construct various statistical test statistics.


