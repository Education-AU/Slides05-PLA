---
title: QR Decomposition, Wide Matrices
template: default
---

For a **wide matrix** $(D \in \mathbb{R}^{n \times p}$ with $p > n$):

1. The full QR decomposition exists:<br>
   $$
   D = Q R, \quad Q \in \mathbb{R}^{n \times n},\ R \in \mathbb{R}^{n \times p} \text{ (upper trapezoidal)}
   $$
2. The top-left $n \times n$ block of $R$ is square and upper triangular
3. The extra columns of $R$ form the “trapezoid” and are required to reconstruct $D$
4. Reduced QR (discarding columns) **does not generally work** for wide matrices
5. **For our purposes**, we will focus on tall matrices ($n \ge p$) and ignore the wide case.

