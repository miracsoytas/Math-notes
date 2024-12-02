# Mathematics Activities (1-10)
 
---
 
## **1. Basic Operations on Matrices**
 
### Matrices:
$$
A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, \,  
B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}, \,  
C = \begin{bmatrix} -1 & 2 \\ 3 & 0 \end{bmatrix}, \,  
D = \begin{bmatrix} -1 & 2 & 3 \\ 4 & 0 & 6 \end{bmatrix}, \,  
E = \begin{bmatrix} 1 & 2 & 4 \\ 5 & 7 & 8 \end{bmatrix}
$$
 
### 1.1 Additions and Subtractions
$$
A + B = \begin{bmatrix} 6 & 8 \\ 10 & 12 \end{bmatrix}
$$
$$
B - A = \begin{bmatrix} 4 & 4 \\ 4 & 4 \end{bmatrix}
$$
$$
A + C = \begin{bmatrix} 0 & 4 \\ 6 & 4 \end{bmatrix}
$$
 
### 1.2 Scalar Multiplications
$$
\frac{1}{3} A = \begin{bmatrix} 0.333 & 0.667 \\ 1 & 1.333 \end{bmatrix}
$$
$$
2B = \begin{bmatrix} 10 & 12 \\ 14 & 16 \end{bmatrix}
$$
$$
-3C = \begin{bmatrix} 3 & -6 \\ -9 & 0 \end{bmatrix}
$$
$$
4D = \begin{bmatrix} -4 & 8 & 12 \\ 16 & 0 & 24 \end{bmatrix}
$$
 
### 1.3 Products
$$
A \cdot B = \begin{bmatrix} 19 & 22 \\ 43 & 50 \end{bmatrix}
$$
$$
B \cdot A = \begin{bmatrix} 23 & 34 \\ 31 & 46 \end{bmatrix}
$$
$$
A \cdot D = \begin{bmatrix} 7 & 2 \\ 13 & 6 \end{bmatrix}
$$
$$
D \cdot E^\text{T} = \begin{bmatrix} 15 & 33 \\ 28 & 68 \end{bmatrix}
$$
 
---
 
## **2. Determinants of Matrices**
 
### 2x2 Matrices
$$
A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, \,  
B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}, \,  
C = \begin{bmatrix} -1 & 2 \\ 3 & 0 \end{bmatrix}
$$
 
$$
\text{det}(A) = (1 \cdot 4) - (2 \cdot 3) = -2
$$
$$
\text{det}(B) = (5 \cdot 8) - (6 \cdot 7) = -2
$$
$$
\text{det}(C) = (-1 \cdot 0) - (2 \cdot 3) = -6
$$
 
### 3x3 Matrices
$$
D = \begin{bmatrix} 1 & 0 & 2 \\ -3 & 1 & -1 \\ 2 & 4 & -2 \end{bmatrix}, \,  
E = \begin{bmatrix} 3 & 1 & -1 \\ 0 & 2 & 4 \\ 5 & 3 & 2 \end{bmatrix}, \,  
F = \begin{bmatrix} 2 & -3 & 1 \\ 1 & 4 & -2 \\ 1 & 5 & 3 \end{bmatrix}
$$
 
$$
\text{det}(D) = -26
$$
$$
\text{det}(E) = 6
$$
$$
\text{det}(F) = 60
$$
 
---
 
## **3. Inverse of a Matrix Using the Formula**
 
### Given Matrix:
$$
A = \begin{bmatrix} 2 & 0 & 1 \\ 0 & 1 & 0 \\ 1 & 2 & 0 \end{bmatrix}
$$
 
#### Steps:
1. Calculate the determinant:
$$
\text{det}(A) = -1
$$
 
2. Calculate the adjoint matrix:
$$
\text{Adj}(A) = \begin{bmatrix} -2 & -2 & 1 \\ -1 & 2 & -2 \\ 1 & -2 & 2 \end{bmatrix}
$$
 
3. Find the inverse:
$$
A^{-1} = \frac{1}{\text{det}(A)} \cdot \text{Adj}(A) = -1 \cdot \begin{bmatrix} -2 & -2 & 1 \\ -1 & 2 & -2 \\ 1 & -2 & 2 \end{bmatrix}
$$
$$
A^{-1} = \begin{bmatrix} 2 & 2 & -1 \\ 1 & -2 & 2 \\ -1 & 2 & -2 \end{bmatrix}
$$
 
---
 
## **4. Eigenvalues and Eigenvectors**
 
### Matrix:
$$
A = \begin{bmatrix} 6 & 2 \\ 2 & 3 \end{bmatrix}
$$
 
1. Solve the characteristic equation:
$$
\text{det}(A - \lambda I) = 0
$$
$$
\begin{vmatrix} 6 - \lambda & 2 \\ 2 & 3 - \lambda \end{vmatrix} = 0
$$
 
2. Eigenvalues:
$$
\lambda_1 = 7, \, \lambda_2 = 2
$$
 
3. Eigenvectors:
For \( \lambda_1 = 7 \):
$$
\text{Eigenvector: } v_1 = \begin{bmatrix} 2 \\ 1 \end{bmatrix}
$$
 
For \( \lambda_2 = 2 \):
$$
\text{Eigenvector: } v_2 = \begin{bmatrix} -1 \\ 1 \end{bmatrix}
$$
 
---
 

## 5. Inverse of a Matrix
Matrix \( A \):
$$
A = \begin{bmatrix} 2 & 0 & 1 \\ 0 & 1 & 0 \\ 1 & 2 & 0 \end{bmatrix}
$$
 
### Solution:
$$
A^{-1} = \begin{bmatrix} 0 & 0 & 1 \\ 0 & 1 & 0 \\ 1 & -2 & -2 \end{bmatrix}

$$
 
---
 
## **6. Rank of a Matrix**
 
#### Given Matrix:
$$
A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}
$$
 
1. Apply row operations to reduce to row echelon form:
$$
\begin{bmatrix} 1 & 2 & 3 \\ 0 & -3 & -6 \\ 0 & 0 & 0 \end{bmatrix}
$$
 
2. Count non-zero rows:
$$
\text{Rank}(A) = 2
$$
 
---
 
## **7. Cross Product of Vectors**
 
#### Given Vectors:
$$
u = \begin{bmatrix} 1 \\ 2 \\ 3 \end{bmatrix}, \,  
v = \begin{bmatrix} 4 \\ 5 \\ 6 \end{bmatrix}
$$
 
1. Cross product formula:
$$
u \times v = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 1 & 2 & 3 \\ 4 & 5 & 6 \end{vmatrix}
$$
 
2. Result:
$$
u \times v = \begin{bmatrix} -3 \\ 6 \\ -3 \end{bmatrix}
$$


