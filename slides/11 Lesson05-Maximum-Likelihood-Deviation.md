---
title: Maximum Likelihood Estimate of σ
template: default
---

Given the estimate $\hat{\mu}$, the parameter $\sigma^2$ can be estimated by maximizing the log-likelihood:

$$
\ln f(y) = n \ln \left( \frac{1}{\sigma \sqrt{2\pi}} \right)
- \frac{1}{2\sigma^2} \| y - \hat{\mu} \|^2
$$

$$
\ln f(y) = - n \ln \sigma - n \ln \sqrt{2\pi} - \frac{1}{2\sigma^2} \| y - \hat{\mu} \|^2
$$

Differentiating with respect to $\sigma$ and setting the derivative to zero gives:

$$
\frac{d}{d\sigma} \ln f(y) = -\frac{n}{\sigma} + \frac{1}{\sigma^3} \| y - \hat{\mu} \|^2 = 0
$$

Solving for $\sigma$ yields:

$$
\hat{\sigma}^2 = \frac{1}{n} \| y - \hat{\mu} \|^2
$$


