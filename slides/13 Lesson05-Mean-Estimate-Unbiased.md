---
title: μ̂ is an Unbiased Estimator
template: default
---
For $\hat{\mu}$ to be an unbiased estimator, it must satisfy:

$$
\mathbb{E}\left( \hat{\mu} \right) = \mu
$$

Since $\hat{\mu}$ is obtained by projecting $y$ onto the subspace $W$, we have:

$$
\hat{\mu} = Py
$$

Then

$$
\mathbb{E}\left( \hat{\mu} \right) = \mathbb{E}\left( Py \right) = P \, \mathbb{E}(y) = P \mu
$$

because $P$ is linear.



By hypothesis, $\mu \in W$ and $P$ is a projection onto $W$, so $P\mu = \mu$, which implies

$$
\mathbb{E}\left( \hat{\mu} \right) = \mu
$$

Thus, $\hat{\mu}$ is an unbiased estimator.



