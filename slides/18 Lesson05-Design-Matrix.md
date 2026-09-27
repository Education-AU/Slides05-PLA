---
title: Model Design Matrix Form
template: default
---



The hypothesis can be expressed in matrix form as:

$$
\mu =
\begin{bmatrix}
1 & h_1 & w_1 & a_1 & a_1^2 \\
1 & h_2 & w_2 & a_2 & a_2^2 \\
\vdots & \vdots & \vdots & \vdots & \vdots \\
1 & h_n & w_n & a_n & a_n^2
\end{bmatrix}
\begin{bmatrix}
\beta_1 \\ \beta_2 \\ \beta_3 \\ \beta_4 \\ \beta_5
\end{bmatrix}
$$


This is usually expressed more compactly as:
<div class="h3-blue">

$H_1$

</div>


$$
\mu = D \beta
$$

where $D$ is the **design matrix** of the hypothesis, and $\beta$ contains the coordinates of $\mu$ in the subspace spanned by the vectors $\mathbf{b}_i$.
