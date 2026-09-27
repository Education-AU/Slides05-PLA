---
title: The Unbiased Estimator σ̂²
template: default
---


The estimator obtained from the previous calculations,

$$
\hat{\sigma}^2_{\text{biased}} = \frac{1}{n} \| y - \hat{\mu} \|^2,
$$

is a **biased estimator**, i.e.,

$$
\mathbb{E}\left( \hat{\sigma}^2_{\text{biased}} \right) \neq \sigma^2.
$$

An unbiased estimator of the variance is

$$
\hat{\sigma}^2 = \frac{1}{n-p} \| y - \hat{\mu} \|^2,
$$

where $p$ is the dimension of the subspace $W$ .

This estimator satisfies

$$
\mathbb{E}\left( \hat{\sigma}^2 \right) = \sigma^2.
$$

Notice that for large $n$, the difference between the biased and unbiased estimator becomes negligible.

