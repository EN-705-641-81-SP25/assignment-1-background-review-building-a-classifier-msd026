# EN.705.641.81

## 1 Refreshing the Rows and Columns: Linear Algebra Review

### 1.1 Basic Operations

Given:
- α = 2
- x = [0, 1, 2]ᵀ
- y = [3, 4, 5]ᵀ
- z = [1, 2, -1]ᵀ
- A = [[3, 2, 2], [1, 3, 1], [1, 1, 3]]

1. **Inner Product**: ∑ᵢ xᵢ yᵢ = 0*3 + 1*4 + 2*5 = 0 + 4 + 10 = **14**
2. **Inner Product (Orthogonal Vectors)**: ∑ᵢ xᵢ zᵢ = 0*1 + 1*2 + 2*(-1) = 0 + 2 - 2 = **0**
3. **Scalar Multiplication and Vector Addition**: α(x + y) = 2([0+3, 1+4, 2+5]) = 2[3, 5, 7] = **[6, 10, 14]**
4. **Euclidean Norm**: ∥x∥ = √(0² + 1² + 2²) = √(0 + 1 + 4) = **√5**
5. **Vector Transpose**: xᵀ = **[0, 1, 2]**
6. **Matrix-Vector Multiplication**: Ax = [3*0 + 2*1 + 2*2, 1*0 + 3*1 + 1*2, 1*0 + 1*1 + 3*2] = [0 + 2 + 4, 0 + 3 + 2, 0 + 1 + 6] = **[6, 5, 7]**
7. **Quadratic Form**: xᵀAx = [0, 1, 2] * [6, 5, 7] = 0*6 + 1*5 + 2*7 = 0 + 5 + 14 = **19**

### 1.2 Matrix Algebra Rules

1. **True**: xᵀy = ∑ᵢ xᵢ yᵢ
2. **True**: xᵀx = ∥x∥²
3. **False**: xᵀx is a scalar, while xxᵀ is a matrix.
4. **True**: (x - y)ᵀ(y - x) = ∥x∥² - 2xᵀy + ∥y∥²
5. **False**: Matrix multiplication is not commutative in general.
6. **True**: A(B + C) = AB + AC (Distributive property)
7. **False**: (AB)ᵀ = BᵀAᵀ
8. **True**: xᵀAy = yᵀAᵀx
9. **True**: If AᵀA = I, the columns of A are orthonormal.

### 1.3 Matrix Operations

Given:
- B = [[1, -1, 0], [-1, 2, -1], [0, -1, 1]]

- **Invertibility**: B is invertible. The inverse B⁻¹ is: