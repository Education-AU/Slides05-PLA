---
title: R², Measure of Model Fit
template: default
---

$R^2$ is a simple measure of how well the model explains the variation in the data.  
It is not a formal test statistic, but it is closely related to the $F$-test.

It is defined as:

$$
R^2 = \frac{\| y - D_1 \hat{\beta}_1 \|^2 - \| y - D \hat{\beta} \|^2}{\| y - D_1 \hat{\beta}_1 \|^2}
= 1 - \frac{\| y - D \hat{\beta} \|^2}{\| y - D_1 \hat{\beta}_1 \|^2}
= 1 - \frac{\| y - D \hat{\beta} \|^2}{\| y - \bar{y} \mathbf{1} \|^2}
$$

where $D_1$ is the design matrix of ones, corresponding to the mean $\bar{y}$ of the observations.

**Properties:**
$$
0 \le R^2 \le 1
$$

- $R^2 \approx 1$: model explains most of the variability
- $R^2 \approx 0$: model explains very little of the variability

