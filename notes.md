# Matematik Notları

# Basic Operations on Matrices

### Given Matrices:
\[
A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, 
B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}, 
C = \begin{bmatrix} -1 & 2 \\ 3 & 0 \end{bmatrix}, 
D = \begin{bmatrix} -1 & 2 & 3 \\ 4 & 0 & 6 \end{bmatrix}, 
E = \begin{bmatrix} 1 & 2 & 4 \\ 5 & 7 & 8 \end{bmatrix}
\]

### 1.1 Additions and Subtractions
- \( A + B = \begin{bmatrix} 6 & 8 \\ 10 & 12 \end{bmatrix} \)
- \( B - A = \begin{bmatrix} 4 & 4 \\ 4 & 4 \end{bmatrix} \)
- \( A + C = \begin{bmatrix} 0 & 4 \\ 6 & 4 \end{bmatrix} \)

### 1.2 Scalar Multiplications
- \( \frac{1}{3} A = \begin{bmatrix} 0.333 & 0.667 \\ 1 & 1.333 \end{bmatrix} \)
- \( 2B = \begin{bmatrix} 10 & 12 \\ 14 & 16 \end{bmatrix} \)
- \( -3C = \begin{bmatrix} 3 & -6 \\ -9 & 0 \end{bmatrix} \)
- \( 4D = \begin{bmatrix} -4 & 8 & 12 \\ 16 & 0 & 24 \end{bmatrix} \)

### 1.3 Products
- \( A \cdot B = \begin{bmatrix} 19 & 22 \\ 43 & 50 \end{bmatrix} \)
- \( B \cdot A = \begin{bmatrix} 23 & 34 \\ 31 & 46 \end{bmatrix} \)
- \( A \cdot D = \begin{bmatrix} 7 & 2 \\ 13 & 6 \end{bmatrix} \)
- \( D \cdot E^\text{T} = \begin{bmatrix} 15 & 33 \\ 28 & 68 \end{bmatrix} \) (using transposed \( E \) for compatibility)


# Determinants of Matrices

### 2x2 Matrices
\[
A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, 
B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}, 
C = \begin{bmatrix} -1 & 2 \\ 3 & 0 \end{bmatrix}
\]

- \( \text{det}(A) = (1 \cdot 4) - (2 \cdot 3) = -2 \)
- \( \text{det}(B) = (5 \cdot 8) - (6 \cdot 7) = -2 \)
- \( \text{det}(C) = (-1 \cdot 0) - (2 \cdot 3) = -6 \)

### 3x3 Matrices
\[
D = \begin{bmatrix} 1 & 0 & 2 \\ -3 & 1 & -1 \\ 2 & 4 & -2 \end{bmatrix}, 
E = \begin{bmatrix} 3 & 1 & -1 \\ 0 & 2 & 4 \\ 5 & 3 & 2 \end{bmatrix}, 
F = \begin{bmatrix} 2 & -3 & 1 \\ 1 & 4 & -2 \\ 1 & 5 & 3 \end{bmatrix}
\]

- \( \text{det}(D) = -26 \)
- \( \text{det}(E) = 6 \)
- \( \text{det}(F) = 60 \)


## 3. Determinants using Laplace's Expansion

### Matrices
\[
A = \begin{bmatrix} 2 & 3 & 1 \\ 1 & 4 & 0 \\ 3 & 2 & 1 \end{bmatrix},  
B = \begin{bmatrix} 2 & 3 & 1 \\ 1 & 4 & 0 \\ 3 & 2 & 0 \end{bmatrix},  
C = \begin{bmatrix} 2 & 3 & 1 & 4 \\ 1 & 0 & 0 & 6 \\ 3 & 2 & 1 & 5 \\ 2 & 1 & 4 & 0 \end{bmatrix},  
D = \begin{bmatrix} 2 & 3 & 1 & 4 & 5 \\ 1 & 0 & 0 & 6 & 7 \\ 3 & 2 & 1 & 5 & 8 \\ 2 & 1 & 4 & 0 & 9 \\ 1 & 4 & 7 & 8 & 9 \end{bmatrix}  
\]

#### Determinants:
- \( \text{det}(A) = -3 \)  
- \( \text{det}(B) = 0 \)  
- \( \text{det}(C) = -98 \)  
- \( \text{det}(D) = -900 \)  

---

## 4. Determinants from the Gauss Method and Triangular Matrices

### Matrices
\[
A = \begin{bmatrix} 12 & 3 \\ -18 & -4 \end{bmatrix},  
B = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}  
\]

#### Gauss Reduction Steps:
1. For \( A \):  
   - Row reduction yields upper triangular form.  
   - Diagonal product: \( \text{det}(A) = 12 \cdot (-4) - 0 = -48 \)  

2. For \( B \):  
   - Row reduction yields \( \text{det}(B) = 0 \) (since the rows are linearly dependent).  

---

## 5. Inverse of a Matrix from the Formula

### Matrix
\[
A = \begin{bmatrix} 2 & 0 & 1 \\ 0 & 1 & 0 \\ 1 & 2 & 0 \end{bmatrix}  
\]

#### Steps:
1. Calculate the determinant:  
   \( \text{det}(A) = (2 \cdot 1 \cdot 0) + (0 \cdot 0 \cdot 1) + (1 \cdot 0 \cdot 2) - (1 \cdot 1 \cdot 1) - (2 \cdot 0 \cdot 0) - (0 \cdot 2 \cdot 2) = -1 \).  

2. Calculate the adjoint matrix:  
   \( \text{Adj}(A) = \begin{bmatrix} -2 & -2 & 1 \\ -1 & 2 & -2 \\ 1 & -2 & 2 \end{bmatrix} \).  

3. Find the inverse:  
   \[
   A^{-1} = \frac{1}{\text{det}(A)} \cdot \text{Adj}(A) = -1 \cdot \begin{bmatrix} -2 & -2 & 1 \\ -1 & 2 & -2 \\ 1 & -2 & 2 \end{bmatrix} = \begin{bmatrix} 2 & 2 & -1 \\ 1 & -2 & 2 \\ -1 & 2 & -2 \end{bmatrix}  
   \]

4. Verify correctness by checking \( A \cdot A^{-1} = I \).  

---

## 6. Inverse of a Matrix using the Gauss Method

### Matrices
\[
A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix},  
B = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 1 \\ 2 & 3 & 2 \end{bmatrix},  
C = \begin{bmatrix} 0 & 0 & 1 \\ 0 & 1 & 0 \\ 1 & 0 & 0 \end{bmatrix}  
\]

#### Steps:
1. For \( A \):  
   - Apply row operations to find the inverse matrix.  
   - \( A^{-1} = \begin{bmatrix} -2 & 1 \\ 1.5 & -0.5 \end{bmatrix} \)  

2. For \( B \):  
   - Apply row operations to find the inverse matrix.  
   - \( B^{-1} = \text{(calculated result)} \)  

3. For \( C \):  
   - \( C^{-1} = \begin{bmatrix} 0 & 0 & 1 \\ 0 & 1 & 0 \\ 1 & 0 & 0 \end{bmatrix} \)  


   ## 7. Eigenvalues and Eigenvectors of a Matrix

### Matrix
\[
A = \begin{bmatrix} 4 & 1 \\ 2 & 3 \end{bmatrix}
\]

#### Eigenvalues Calculation:
1. Solve \( \text{det}(A - \lambda I) = 0 \):
\[
\begin{vmatrix} 4 - \lambda & 1 \\ 2 & 3 - \lambda \end{vmatrix} = (4 - \lambda)(3 - \lambda) - (2 \cdot 1) = \lambda^2 - 7\lambda + 10 = 0
\]
2. Solve the quadratic equation:
\[
\lambda^2 - 7\lambda + 10 = 0 \implies (\lambda - 5)(\lambda - 2) = 0
\]
3. Eigenvalues:
\[
\lambda_1 = 5, \quad \lambda_2 = 2
\]

#### Eigenvectors Calculation:
1. For \( \lambda_1 = 5 \):
   - Solve \( (A - 5I)x = 0 \):
\[
\begin{bmatrix} -1 & 1 \\ 2 & -2 \end{bmatrix} \begin{bmatrix} x_1 \\ x_2 \end{bmatrix} = 0 \implies x_1 = x_2
\]
   - Eigenvector: \( x_1 = \begin{bmatrix} 1 \\ 1 \end{bmatrix} \)

2. For \( \lambda_2 = 2 \):
   - Solve \( (A - 2I)x = 0 \):
\[
\begin{bmatrix} 2 & 1 \\ 2 & 1 \end{bmatrix} \begin{bmatrix} x_1 \\ x_2 \end{bmatrix} = 0 \implies x_1 = -\frac{1}{2}x_2
\]
   - Eigenvector: \( x_2 = \begin{bmatrix} 1 \\ -2 \end{bmatrix} \)

---

## 8. Matrix Diagonalization

### Matrix
\[
A = \begin{bmatrix} 4 & 1 \\ 2 & 3 \end{bmatrix}
\]

#### Steps for Diagonalization:
1. Find eigenvalues and eigenvectors (calculated in the previous problem).
2. Form the matrix \( P \) with eigenvectors as columns:
\[
P = \begin{bmatrix} 1 & 1 \\ 1 & -2 \end{bmatrix}
\]
3. Form the diagonal matrix \( D \) with eigenvalues:
\[
D = \begin{bmatrix} 5 & 0 \\ 0 & 2 \end{bmatrix}
\]
4. Verify \( A = PDP^{-1} \) by calculating \( P^{-1} \) and \( PDP^{-1} \).

---

## 9. Solving Linear Systems with Matrix Inversion

### System of Equations
\[
\begin{cases}
2x + 3y = 8 \\
3x + 4y = 11
\end{cases}
\]

### Matrix Form
\[
A = \begin{bmatrix} 2 & 3 \\ 3 & 4 \end{bmatrix}, \quad \mathbf{b} = \begin{bmatrix} 8 \\ 11 \end{bmatrix}
\]

#### Steps:
1. Find \( A^{-1} \):
\[
\text{det}(A) = 2 \cdot 4 - 3 \cdot 3 = 8 - 9 = -1
\]
\[
A^{-1} = \frac{1}{-1} \begin{bmatrix} 4 & -3 \\ -3 & 2 \end{bmatrix} = \begin{bmatrix} -4 & 3 \\ 3 & -2 \end{bmatrix}
\]

2. Solve for \( \mathbf{x} \):
\[
\mathbf{x} = A^{-1} \mathbf{b} = \begin{bmatrix} -4 & 3 \\ 3 & -2 \end{bmatrix} \begin{bmatrix} 8 \\ 11 \end{bmatrix} = \begin{bmatrix} -4 \cdot 8 + 3 \cdot 11 \\ 3 \cdot 8 - 2 \cdot 11 \end{bmatrix} = \begin{bmatrix} 1 \\ 5 \end{bmatrix}
\]

#### Solution:
\[
x = 1, \quad y = 5
\]

---

## 10. Solving Linear Systems with Gaussian Elimination

### System of Equations
\[
\begin{cases}
x + 2y + 3z = 9 \\
2x + 3y + 4z = 13 \\
3x + 4y + 5z = 17
\end{cases}
\]

#### Gaussian Elimination Steps:
1. Convert to augmented matrix form:
\[
\left[ \begin{array}{ccc|c}
1 & 2 & 3 & 9 \\
2 & 3 & 4 & 13 \\
3 & 4 & 5 & 17 \\
\end{array} \right]
\]

2. Row operations to get upper triangular form:
   - \( R_2 \leftarrow R_2 - 2R_1 \)
   - \( R_3 \leftarrow R_3 - 3R_1 \)

3. Back-substitution to solve for \( x, y, z \).

---

