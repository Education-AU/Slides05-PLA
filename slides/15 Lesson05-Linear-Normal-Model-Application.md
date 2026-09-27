---
title: Linear Normal Model Application
template: default
---



Having discussed the theory, we now turn to applications.



Consider a dataset of body fat **density** and related properties: **height, weight, age**.



We model the data using the following hypothesis:

<div class="h3-blue">
$H_0$
</div>

The density measurements $y_i$ are assumed to be independent and normally distributed:

$$
Y_i \sim \mathcal{N}(\mu_i, \sigma^2)
$$

with a common variance $\sigma^2$.

We represent the measurements as a vector $y \in \mathbb{R}^n$, and assume that the mean vector $\mu$ lies in a subspace $W \subset \mathbb{R}^n$.


This provides the basis for the general linear normal model.


