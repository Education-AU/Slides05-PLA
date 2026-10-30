---
title: F-Test Model Comparison Example
template: default
---

An F-test compares two nested models to determine:

Whether the restrictions imposed on the simpler model lead to a
statistically significant loss of explanatory power compared with the more general model.

As a first example, consider the following hypotheses:

<div class="h3-blue">
$H_R$ and $H_F$
</div>

Restricted model $D_R$ and full model $D_F$
$$
D_R =
\begin{bmatrix}
1 \\
1 \\
\vdots \\
1
\end{bmatrix}
D_F =
\begin{bmatrix}
1 & h_1 & w_1 & a_1 & a_1^2 \\
1 & h_2 & w_2 & a_2 & a_2^2 \\
\vdots & \vdots & \vdots & \vdots & \vdots \\
1 & h_n & w_n & a_n & a_n^2
\end{bmatrix}
$$

The restricted model assumes a constant mean, while the full model incorporates height, weight, age and age squared.

