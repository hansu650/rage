# Determinant

## Laplace's theorem

\[ \det(A) = 
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
\]

firstly, let's consider:

\[ \det(M) = 
\begin{vmatrix}
a_{11} & \cdots & a_{1n} & 0 & \cdots & 0 \\
\vdots & \ddots & \vdots & \vdots & \ddots & \vdots \\
a_{n1} & \cdots & a_{nn} & 0 & \cdots & 0 \\
b_{11} & \cdots & b_{1m} & c_{11} & \cdots & c_{1m} \\
\vdots & \ddots & \vdots & \vdots & \ddots & \vdots \\
b_{n1} & \cdots & b_{nm} & c_{m1} & \cdots & c_{mm} 
\end{vmatrix}
\]

Obviously, $\det(M) = \det(A)\det(C)$

## Cramer's law