---
title: Estimators
template: default
---



The estimators corresponding to the least squares estimate $\hat{\beta}$ are:

$$
\hat{\beta} = (D^T D)^{-1} D^T Y
$$

$$
\hat{\mu} = D \hat{\beta}
$$

The estimator for the variance is:

$$
\hat{\sigma}^2 = \frac{1}{n-p} \| Y - D \hat{\beta} \|^2
$$

where $Y = (Y_1, Y_2, \dots, Y_n)$ are the random variables associated with the observed measurements $y_i$.

