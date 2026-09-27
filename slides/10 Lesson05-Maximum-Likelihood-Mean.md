---
title: Maximum Likelihood Estimate of μ
template: default
---

The maximum likelihood estimate $\hat{\mu}$ of the mean vector $\mu$ is the value of $\mu$ that maximizes the likelihood
function $f$. Equivalently, it is the $\mu$ that minimizes the squared norm:

$$
\hat{\mu} =\min_{\mu}\| y - \mu\|^2
$$

Assuming that $\mu$ lies in a subspace $W \subset \mathbb{R}^n$, this minimization becomes a standard least squares
problem, as discussed previously.

We will specify the structure of this subspace in the applications section.
