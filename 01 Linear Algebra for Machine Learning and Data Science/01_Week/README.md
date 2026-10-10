# 📐 Course 1, Week 1: Systems of Linear Equations

Welcome to **Week 1** of **Linear Algebra for Machine Learning and Data Science** (Course 1 of the DeepLearning.AI Mathematics for Machine Learning and Data Science Specialization)! This module establishes the foundational bridge between algebraic equations and matrix representations. You will study how linear systems naturally emerge from real-world data science problems, explore their geometric interpretations as intersecting lines and planes, distinguish between singular and non-singular configurations, and implement matrix operations using NumPy arrays.

---

## 📝 Core Technical Objectives
- **Geometric Interpretation of Linear Systems:** Visualizing $2 \times 2$ and $3 \times 3$ linear systems as lines in a 2D plane and planes in a 3D space. Identifying unique intersections (single solution), parallel lines/planes (no solution), and coincident lines/planes (infinite solutions).

- **Matrix Representations & Linear Independence:** Translating systems of equations into matrix-vector forms ($Ax = b$). Distinguishing between linearly independent vectors (spanning full dimensionality) and linearly dependent vectors (redundant information leading to singular matrices).

- **Singularity & Determinant Calculation:** Evaluating the geometric and algebraic implications of singularity. Calculating determinants for $2 \times 2$ and $3 \times 3$ matrices to determine whether a matrix is invertible or singular ($\det(A) = 0$).

- **NumPy Foundations for Linear Algebra:** Implementing vector and matrix data structures, indexing, slicing, and basic linear algebra functions using NumPy arrays.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core video lectures, lecture notes, and hands-on NumPy/linear system labs are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **[Lecture Notes & Slides](./01%20Linear%20Algebra%20for%20Machine%20Learning%20and%20Data%20Science/01_Week/Lecture%20Files/C1w1notes.pdf)** | Formal visual reference covering linear equation definitions, graphical representations of lines and planes, linear dependence, matrix singularity proofs, and determinant formulas. |
| **[Introduction to NumPy Arrays Lab](./01%20Linear%20Algebra%20for%20Machine%20Learning%20and%20Data%20Science/01_Week/Labs/C1_W1_Lab_1_introduction_to_numpy_arrays.ipynb)** | Hands-on Python implementation covering NumPy array creation, multidimensional indexing, broadcasting, element-wise arithmetic, and basic matrix operations. |
| **[Solving Linear Systems (2 Variables) Lab](./01%20Linear%20Algebra%20for%20Machine%20Learning%20and%20Data%20Science/01_Week/Labs/C1_W1_Lab_2_solving_linear_systems_2_variables.ipynb)** | Programming $2 \times 2$ linear systems in Python, setting up coefficient matrices and constant vectors, plotting lines via Matplotlib, and solving systems using NumPy matrix inversions. |

---

## 💡 Visual Pipeline Reference

The foundational algebraic structures and matrix transformations governing Week 1:

- **System of Linear Equations to Matrix Form ($Ax = b$)**:

$$\begin{cases}    a_{11}x_1 + a_{12}x_2 = b_1 \\    a_{21}x_1 + a_{22}x_2 = b_2    \end{cases} \implies \begin{bmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{bmatrix} \begin{bmatrix} x_1 \\ x_2 \end{bmatrix} = \begin{bmatrix} b_1 \\ b_2 \end{bmatrix}$$

- **Determinant Calculation for $2 \times 2$ Matrices**:

$$\det(A) = \begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc$$

- **Geometric Solutions Classification**:

| System Type | Graphical Intersection (2D) | Determinant / Rank Property | Solution Count |
| :--- | :--- | :--- | :--- |
| **Consistent & Independent** | Intersecting lines at a single point | $\det(A) \neq 0$ (Non-singular) | Exactly 1 Unique Solution |
| **Inconsistent** | Strictly parallel lines | $\det(A) = 0$, Dependent rows | Zero Solutions (No Intersection) |
| **Dependent** | Overlapping / coincident lines | $\det(A) = 0$, Linearly dependent | Infinitely Many Solutions |

---

## 🎯 Technical Skills Architecture

### 📊 Linear Algebra Theory & Geometric Analysis
- **System Mapping:** Translating word problems and physical constraints into structured systems of linear equations and matrix arrays.
- **Singularity Diagnostics:** Recognizing when matrices lose full rank and evaluating how zero determinants impact invertibility.
- **Linear Dependence Verification:** Testing whether sets of vectors lie on the same lower-dimensional subspace.

### 🤖 Applied Python & NumPy Engineering
- **Array Manipulation:** Initializing vectors and matrices using `np.array`, `np.zeros`, `np.ones`, and `np.arange`.
- **Matrix Operations:** Performing dot products, transpositions, and solving linear matrix equations utilizing `np.linalg.solve()`.
- **Visualization:** Plotting linear equations and intersection points using `matplotlib.pyplot`.

---

## 🛠️ Production Tech Stack & Ecosystem

| Mathematical Framework | Programming Library | Visualization Tool | Interactive Environment |
| :---: | :---: | :---: | :---: |
| ![Linear Algebra](https://img.shields.io/badge/Linear_Algebra-Systems_of_Equations-blue?style=flat) | ![NumPy](https://img.shields.io/badge/NumPy-Arrays_&_Linear_Algebra-013243?style=flat&logo=numpy&logoColor=white) | ![Matplotlib](https://img.shields.io/badge/Matplotlib-Plotting_Lines_&_Planes-11557c?style=flat) | ![Jupyter](https://img.shields.io/badge/Jupyter-Interactive_Labs-FA0F00?style=flat&logo=jupyter&logoColor=white) |
