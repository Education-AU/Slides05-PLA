---
title: Orthogonal Projection
template: default
---


The projection problem  is to find the vector $\mathbf{w}_0 \in W$ that is closest to the vector $\mathbf{u}$ in the norm induced by the standard inner product.



That is
$$
\mathbf{w}_0= \min_{\mathbf{w}\in W}\| \mathbf{u}-\mathbf{w} \|_{2}
$$  
We saw in a previous lesson that we could formulate this problem in a matrix setting.

Let $W=\operatorname{span}(\{\mathbf{b}_1,\dots,\mathbf{b}_k\})$.
Fix a basis for $V$ and express the vectors $\mathbf{b}_1,\dots,\mathbf{b}_k$ in this basis to form the matrix
$$
A=
\begin{bmatrix}
b_{11} & b_{12} & \cdots & b_{1k}\\
b_{21} & b_{22} & \cdots & b_{2k}\\
\vdots & \vdots & \ddots &  \cdots     \\
b_{n1} & b_{n2} & \cdots & b_{nk}
\end{bmatrix}
$$

