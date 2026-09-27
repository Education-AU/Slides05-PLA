---
title: Distribution of Estimator β̂
template: default
---

The estimator $\hat{\beta}$ is normally distributed, since it is a linear combination of independent normally distributed variables:

$$
\hat{\beta} = (D^T D)^{-1} D^T Y
$$


We have already seen that the mean of $\hat{\mu}$ satisfies:

$$
\mathbb{E}(\hat{\mu}) = \mu
$$

which implies that the mean of $\hat{\beta}$ is:

$$
\mathbb{E}(\hat{\beta}) = \beta
$$


To fully characterize the distribution of each component $\hat{\beta}_i$, we also need the variance. It can be shown that:

$$
\operatorname{Var}(\hat{\beta}_i) = \sigma^2 \, \big((D^T D)^{-1}\big)_{ii}
$$

