---
title: Maximum Likelihood Estimation of Parameters μ and σ
template: default
---


The parameters $\mu_i$ and $\sigma$ are unknown and must be estimated from given data.

After estimation, we must assess the quality of these estimates to use them for further analysis.

<br>
<br>

We need a method to estimate the parameters from the measurements. One such method is the **maximum likelihood
estimation**.

The maximum likelihood estimation of parameters is performed by maximizing the density function over the parameters
having fixed outcomes.

$$
(\hat{\mu},\hat{\sigma})=\max_{\mu,\sigma} (f (y\mid \mu,\sigma)))
$$
That is
$$
(\hat{\mu},\hat{\sigma})=\max_{\mu,\sigma}\left (\frac{1}{\sigma \sqrt{2\pi}} \right)^n
\exp\left (-\frac{1}{2\sigma^2} \| y - \mu \|^2 \right)
$$