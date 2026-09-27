---
title: QR Decomposition and Least Squares
template: default
---

The standard least squares problem is:

$$
\hat{\beta} = (D^T D)^{-1} D^T y
$$

Assume $D$ has full column rank (all columns are linearly independent).


Represent $D$ as $D = Q R$ (reduced QR) and substitute:

$$
\begin{aligned}
\hat{\beta}
&= ((QR)^T (QR))^{-1} (QR)^T y \\
&= (R^T Q^T Q R)^{-1} R^T Q^T y \\
&= (R^T R)^{-1} R^T Q^T y \\
&= R^{-1} (R^T)^{-1} R^T Q^T y \\
&= R^{-1} Q^T y
\end{aligned}
$$