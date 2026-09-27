---
title: QR Decomposition and Least Squares
template: default
---

1. Using QR decomposition, the inversion of $D^T D$ is no longer needed
2. Only the upper triangular matrix $R$ must be inverted
3. Inverting $R$ is efficient and can be done via **back substitution**
4. This greatly improves numerical stability and computational efficiency