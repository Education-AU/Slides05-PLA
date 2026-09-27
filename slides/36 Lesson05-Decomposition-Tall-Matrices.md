---
title: QR Decomposition for Tall or Square Matrices
template: default
---


For any real matrix $D \in \mathbb{R}^{n \times p}$ with $p \le n$:

$$
D = Q R
$$

1. $Q \in \mathbb{R}^{n \times p}$ has **orthonormal columns**: $Q^T Q = I_p$
2. $R \in \mathbb{R}^{p \times p}$ is **upper triangular** and invertible if $D$ has full column rank

**Full (non-reduced) QR:**  
$$
R \in \mathbb{R}^{n \times p}, \quad \text{bottom } n-p \text{ rows are all zeros.}
$$

These extra zero rows are ignored in the reduced $p \times p$ form, which is typically used in computations such as
**solving least squares problems**.

