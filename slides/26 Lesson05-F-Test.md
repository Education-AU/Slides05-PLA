---
title: F-Test Model Comparison Example
template: default
---


We test whether the restrictions imposed by a **restricted** model are compatible with the data, relative to a
**larger** model that contains the restricted model as a special case.
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

