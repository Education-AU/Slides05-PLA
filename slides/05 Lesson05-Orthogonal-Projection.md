---
title: Orthogonal Projection
template: default
---


We previously proved that the unique projection $\mathbf{w}_0$ with coordinates $x_0$ satisfied
$$
\langle y-Ax_0, Ax\rangle=0
$$
where $y$ are coordinates for the vector $\mathbf{u}\in V$ and $x\in \mathbb{R}^k$



This implies
$$
\langle Ax_0, Ax\rangle=\langle y,Ax \rangle \Rightarrow \langle x,A^TAx_0 \rangle=\langle x,A^Ty \rangle
$$

for all $x$ which implies
$$  
A^TAx_0=A^Ty \Rightarrow x_0=(A^TA)^{-1}A^Ty
$$

This is called the normal equation associated with the multivariate least-squares problem.
$$
x_0=(A^TA)^{-1}A^Ty
$$



