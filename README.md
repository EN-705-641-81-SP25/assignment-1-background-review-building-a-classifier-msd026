# EN.705.641.81

## 1 Refreshing the Rows and Columns: Linear Algebra Review

### 1.1 Basic Operations

Matrix:


Given:
- α = 2
- x = 

$$
\begin{bmatrix}
0 \\
1 \\
2
\end{bmatrix}
$$


- y =

$$
\begin{bmatrix}
3 \\
4 \\
5
\end{bmatrix}
$$
- z = 

$$
\begin{bmatrix}
1 \\
2 \\
-1
\end{bmatrix}
$$

- A = 

$$
\begin{bmatrix}
3 & 2 & 2 \\
1 & 3 & 1 \\
1 & 1 & 3
\end{bmatrix}
$$


1. **Inner Product**:

   ∑ᵢ xᵢ yᵢ = 0*3 + 1*4 + 2*5 = 0 + 4 + 10 = **14**
   
2. **Inner Product (Orthogonal Vectors)**:
  
   ∑ᵢ xᵢ zᵢ = 0*1 + 1*2 + 2*(-1) = 0 + 2 - 2 = **0**
   
3. **Scalar Multiplication and Vector Addition**:

   α(x + y) = 2([0+3, 1+4, 2+5]) = 2[3, 5, 7] = **[6, 10, 14]**
   
4. **Euclidean Norm**:

   ∥x∥ = √(0² + 1² + 2²) = √(0 + 1 + 4) = **√5**
   
5. **Vector Transpose**:

    xᵀ = **[0, 1, 2]**
    
6. **Matrix-Vector Multiplication**:

   Ax = [3*0 + 2*1 + 2*2, 1*0 + 3*1 + 1*2, 1*0 + 1*1 + 3*2]  
      = [0 + 2 + 4, 0 + 3 + 2, 0 + 1 + 6]  
      = **[6, 5, 7]**
   
7. **Quadratic Form**: 

$$
x^\top A x = [0, 1, 2] \cdot [6, 5, 7] \\
            = 0 \cdot 6 + 1 \cdot 5 + 2 \cdot 7 \\
            = 0 + 5 + 14 \\
            = 19
$$


### 1.2 Matrix Algebra Rules

1. xᵀy = ∑ᵢ xᵢ yᵢ => **True**
2. xᵀx = ∥x∥² => **True**
3. xᵀx is a scalar, while xxᵀ is a matrix. => **False**
4. (x - y)ᵀ(y - x) = ∥x∥² - 2xᵀy + ∥y∥² => **True**
5. Matrix multiplication is not commutative in general. => **False**
6. A(B + C) = AB + AC (Distributive property) => **True**
7. (AB)ᵀ = BᵀAᵀ => **False**
8. xᵀAy = yᵀAᵀx => **True**
9. If AᵀA = I, the columns of A are orthonormal. => **True**

### 1.3 Matrix Operations

Given:

$$
B =
\begin{bmatrix}
1 & -1 & 0 \\
-1 & 2 & -1 \\
0 & -1 & 1
\end{bmatrix}
$$

- The Invertibility

det(B) = 1⋅(2⋅1 − (−1)⋅(−1)) − (−1)⋅(−1⋅1 − (−1)⋅0) + 0⋅(−1⋅(−1) − 2⋅0)  
       = 1⋅(2 − 1) − (−1)⋅(−1) + 0  
       = 1 − 1  
       = 0

det(B) = 0 => B is not  invertible


- The diagonalization is:

$$
B = P D P^{-1}
$$

where:

$$
P =
\begin{bmatrix}
1 & 1 & 1 \\
0 & 0 & -1 \\
-1 & 0 & 1
\end{bmatrix},
\quad
D =
\begin{bmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 2
\end{bmatrix}.
$$


## 2. Taking Chances: Probability Review

### 2.1 Basic Probability

#### 1. **Expected value**

E(x) = $5

#### 2. **Mutually exclusive Probability**

P(B)=0.55

#### 3. **A and B are independent**

P(B) = 0.9167



### 2.2 Expectations and Variance

### Expected Value E[X]

#### E(X) for a single flip

P(H) = P(C₁)⋅P(H|C₁) + P(C₂)⋅P(H|C₂)  
P(H) = 0.5⋅0.3 + 0.5⋅0.9  
P(H) = 0.15 + 0.45  
P(H) = 0.6

#### E(X) value for 3 flips

The expected number of independent heads in 3 flips is:

E[X] = 3⋅P(H)  
E[X] = 3⋅0.6  
E[X] = 1.8

### Variance

#### Variance for a single flip
Var(X) = P(H)⋅(1 − P(H))  
Var(X) = 0.6⋅0.4  
Var(X) = 0.24

#### Variance for 3 flips
variance for 3 independent flips is:

Var[X] = 3⋅Var(X)  
Var[X] = 3⋅0.24  
Var[X] = 0.72

### 2.3 A Variance Paradox?

I don't understand this one. Will come back to it



## 3. Calculus Review

### Derivatives

1. f'(x) = 6x - 2 

2. f'(x) = 1 - 2x 

3. f'(x) = p(x)

### Gradient Expressions

1. ∇f(x) = [2x₁, exp(x₂)]

2. ∇f(x) = exp(x₁ + x₂x₃) [1, x₃, x₂]

3. ∇f(x) = a

4. ∇f(x) = 2Ax

5. ∇f(x) = 
[
 x₁,
 x₂,
 ⋮,
 xₐ
]
= x


### Algorithms and Data Structures Review

#### 1. Divide-and-Conquer Analysis

a. Divide:  
   Split in 2: O(1).

b. Conquer:  
   Sort halves: 2T(n/2).

c. Combine:  
   combine the 2 O(n).

Using the Master Theorem:

T(n) = 2T(n/2) + O(n) ==> T(n) = O(n log n)


#### 2. Cost of Finding the Third-Largest Element in an Unsorted List
  
   Sort the list in O(n \log n)  time. Then, select the third-largest element can be found in O(1) time by directly accessing the third-to-last element in the sorted list.

#### 3. Cost of Finding the Smallest Element Greater Than 0 in a Sorted List

   Using the Binary search has a time complexity of O(log n)

#### 4. Cost of Finding the Value Associated with a Key in a Hash Table

   O(1)
   
#### 5. Cost of Computing the Matrix-Vector Product Ax

   O(n⋅d)

#### 6. Cost of Computing the Quadratic Form xᵀ(Ax)

   Ax =  O(n^2) 

   xᵀ = O(n)

   xᵀ (Ax) = O(n^2) + O(n) = O(n^2)

#### 7. Cost of Computing Matrix Multiplication AB with A is m×n and B is n×d

   O(m ⋅ n ⋅ d)



