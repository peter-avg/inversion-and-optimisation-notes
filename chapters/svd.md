# SVD and Generalized Inverse

This page deals with Singular Value Decomposition and the Generalized Inverse.
Back to the [contents](../README.md) page.

--- 

## Matrix Diagonalisation and Eigenvalue Decomposition

- **Eigenvalues:** To find the eigenvalues of a a matrix solve the equation 
$det(A - \lambda I) = 0$ for the different $\lambda$s
- **Eigenvectors:** Solve $Av=\lambda v$ for $v$ to find eigenvectors,
for each $\lambda$
- **Diagonalisation:** 
    - For dinstict eigenvalues: $A = P \Lambda P^{-1}$ where $\Lambda$ is a
    diagonal matrix of the eigenvalues of A, and the columns of $P$ are the
    eigenvectors of $A$.
    - For non distinct (repeating eigenvalues): $A = P \Lambda P^T$
- **Singular Value Decomposition:** $A$ can be decomposed to: $A = U \Sigma V^T$
    -  $U$ is an $m \times m$ matrix whose columns are the eigenvectors of $AA^T$
    -  $V$ is an $n \times n$ matrix whose columns are the eigenvectors of $A^TA$
    -  $\Sigma$ is an $m \times n$ diagonal matrix of the singular values of $A$
    -  Singular values of a matrix $A$ are the square roots of the eigenvalues of $A^TA$
    -  $UU^T = U^TU = I$ 
    -  $VV^T = V^TV = I$ 


