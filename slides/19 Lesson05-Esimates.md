---
title: The Estimates μ̂ and σ̂²
template: default
---

From the previous discussion, the least squares estimate of $\beta$ is:

$$
\hat{\beta} = (D^T D)^{-1} D^T y
$$

The corresponding estimate of the mean vector is:

$$
\hat{\mu} = D \hat{\beta}
$$

The unbiased estimate of the variance $\sigma^2$ is:

$$
\hat{\sigma}^2 = \frac{1}{n-p} \| y - D \hat{\beta} \|^2
$$

Here, $p = \dim (W) = 5$ in our example.
