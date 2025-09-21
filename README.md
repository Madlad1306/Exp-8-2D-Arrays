# Exp-8-2D-Arrays
Here’s a **well-structured lab-style write-up** for your topic on **2D Arrays (Matrices in C++)**.

---

# 2D Arrays in C++ (Matrices)

**AIM:**
To understand and implement the usage of 2D arrays (matrices) in C++.

**SOFTWARE USED:**
Visual Studio Code (VS Code)

---

## THEORY

A **matrix** is a rectangular arrangement of numbers, symbols, or expressions in rows and columns. In C++, a matrix is typically implemented using a **two-dimensional (2D) array**, where data is stored in a grid-like structure for easy access and manipulation.

### 🔹 Importance of Matrices

* **Engineering** → Circuit parameters, stress-strain relationships, transformations.
* **Computer Science** → Data tables, image processing, graph representations.
* **Mathematics** → Linear equations, transformations, statistics.
* **Physics** → Quantum mechanics, kinematics modeling.
* **Data Science** → Datasets, correlations, machine learning.

---

### 🔹 Properties of Matrices

* **Order:** Defined as `m × n` (rows × columns).
* **Square Matrix:** Rows = Columns.
* **Diagonal Elements:** Elements where row index = column index.
* **Symmetric Matrix:** Matrix equal to its transpose.
* **Sparse Matrix:** Contains mostly zero elements (memory-efficient storage).

---

### 🔹 Common Matrix Operations

* **Matrix Addition:** Add corresponding elements (requires same order).
* **Matrix Multiplication:** Row × Column multiplication (requires compatible dimensions).
* **Transpose:** Convert rows into columns.
* **Diagonal Operations:** Trace (sum of diagonals), product, determinant (for square matrices).

---

### 🔹 Relevance in Programming

* Implemented using **static arrays** (fixed size) or **dynamic arrays** (runtime allocation).
* Widely used in:

  * Image/Video Processing (pixel matrices)
  * Cryptography & Security
  * Machine Learning (weights, datasets)
  * 3D Graphics & CAD
  * Network & Graph Theory

---

## ALGORITHMS

### 1️⃣ General 2D Array Input and Output

1. Start
2. Declare 2D array `arr[m][n]`
3. Input elements row-wise
4. Display elements in matrix format
5. Stop

---

### 2️⃣ Matrix Addition

1. Start
2. Input dimensions of both matrices (must be the same)
3. Input elements of Matrix A and Matrix B
4. Compute `C[i][j] = A[i][j] + B[i][j]`
5. Display Result Matrix C
6. Stop

---

### 3️⃣ Matrix Multiplication

1. Start
2. Input dimensions of matrices (columns of A = rows of B)
3. Input elements of both matrices
4. For each element of Result Matrix C:
   `C[i][j] = Σ (A[i][k] × B[k][j])`
5. Display Result Matrix C
6. Stop

---

### 4️⃣ Transpose of a Matrix

1. Start
2. Input rows and columns of matrix A
3. Store element `A[i][j]` into `B[j][i]`
4. Display Transpose Matrix B
5. Stop

---

### 5️⃣ Diagonal Operations (Sum / Product)

1. Start
2. Input square matrix A\[n]\[n]
3. Initialize sum = 0 or product = 1
4. For i = 0 to n-1 → process element `A[i][i]`
5. Display result
6. Stop

---

## CONCLUSION

* **2D Arrays (matrices)** in C++ provide a structured way to store and manipulate tabular data.
* Operations like **addition, multiplication, transpose, and diagonal processing** are building blocks for advanced applications.
* Mastering matrices equips programmers with tools for solving real-world problems in **engineering, data science, cryptography, simulations, and graphics**.

---


