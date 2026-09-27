---
title: QR Decomposition
template: default
---


For numerical computations, it is often preferable to factorize matrices rather than compute inverses directly.  
This approach improves both **numerical stability** and **computational efficiency**.

A key tool for this is the **QR decomposition**, which expresses a matrix as a product of an **orthogonal
matrix** and an **upper triangular matrix**:

$$
D = Q R
$$

We will first present the general concept, then focus on the case of **tall matrices**, which is particularly
important for **least squares problems**.
