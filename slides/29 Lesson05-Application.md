---
title: Testing Real Data, Body Fat Example
template: default
---

We now apply our model to real data: body fat **density** measurements, along with **height**, **weight**, and **age** and **height squared**.

The hypotheses are the same as previously formulated:

<div class="h3-blue">
$H_R$ and $H_F$
</div>

Restricted model $D_R$ (constant mean) and full model $D_F$:
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
1 & h_1 & w_1 & a_1 & h_1^2 \\
1 & h_2 & w_2 & a_2 & h_2^2 \\
\vdots & \vdots & \vdots & \vdots & \vdots \\
1 & h_n & w_n & a_n & h_n^2
\end{bmatrix}
$$

