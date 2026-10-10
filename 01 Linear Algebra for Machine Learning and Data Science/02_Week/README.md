# 📉 Course 1, Week 2: Solving Systems of Linear Equations

Welcome to **Week 2** of **Linear Algebra for Machine Learning and Data Science** (Course 1 of the DeepLearning.AI Mathematics for Machine Learning and Data Science Specialization)! This module builds directly upon foundational system geometry to explore systematic algorithmic solutions. You will transition from graphical inspections to rigorous algebraic tools—mastering the elimination method, matrix row reduction, row echelon form, reduced row echelon form (RREF), and the foundational concept of matrix rank for applications like computer vision and data compression.

---

## 📝 Core Technical Objectives
- **Systematic Elimination & Row Operations:** Applying elementary row operations (row swapping, scaling, and adding multiples of one row to another) to solve multi-variable linear systems without altering the solution set or system singularity.

- **Row Echelon Form (REF) & Gaussian Elimination:** Transforming augmented matrices into Upper Triangular or Row Echelon Form using the step-by-step Gaussian Elimination algorithm to solve non-singular and singular linear systems.

- **Reduced Row Echelon Form (RREF):** Reducing matrices further so that the leading entry in each non-zero row is $1$ and is the only non-zero entry in its column, making solutions immediately apparent.

- **Matrix Rank & Solution Determination:** Calculating the rank of a matrix (the maximum number of linearly independent row or column vectors) to determine the existence and uniqueness of solutions (Rouché–Capelli theorem):
  - $\text{Rank}(A) = \text{Rank}(A\vert{}b) = \text{Number of Variables} \implies$ **Unique Solution**
  - $\text{Rank}(A) < \text{Rank}(A\vert{}b) \implies$ **No Solution (Inconsistent)**
  - $\text{Rank}(A) = \text{Rank}(A\vert{}b) < \text{Number of Variables} \implies$ **Infinitely Many Solutions**

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core video lectures, lecture notes, interactive labs, and the primary Gaussian elimination programming assignment are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **[Lecture Notes & Slides](./01%20Linear%20Algebra%20for%20Machine%20Learning%20and%20Data%20Science/02_Week/Lecture%20Files/C1w2notes.pdf)** | Formal visual reference covering algebraic elimination steps, elementary row operations, REF/RREF definitions, Gaussian algorithm rules, and matrix rank theorems. |
| **[Solving Linear Systems (3 Variables) Lab](./01%20Linear%20Algebra%20for%20Machine%20Learning%20and%20Data%20Science/02_Week/Labs/C1_W2_Lab_1_systems_3_variables.ipynb)** | Practical Python implementation solving $3 \times 3$ linear systems, using NumPy to set up augmented matrices, and applying matrix row-reduction scripts. |
| **[Gaussian Elimination Assignment (`C1_W2_Assignment.ipynb`)](./01%20Linear%20Algebra%20for%20Machine%20Learning%20and%20Data%20Science/02_Week/Labs/C1_W2_Assignment.ipynb)** | End-to-end coding assignment implementing custom Gaussian elimination algorithms, calculating matrix ranks, and solving complex linear systems in Python. |

---

## 💡 Visual Pipeline Reference

The structural algebraic transformations governing Week 2:

- **Augmented Matrix Row Reduction to REF**:

$$\left[ \begin{array}{ccc\|c}    a_{11} & a_{12} & a_{13} & b_1 \\    a_{21} & a_{22} & a_{23} & b_2 \\    a_{31} & a_{32} & a_{33} & b_3    \end{array} \right] \xrightarrow{\text{Elementary Row Operations}} \left[ \begin{array}{ccc\|c}    1 & u_{12} & u_{13} & c_1 \\    0 & 1      & u_{23} & c_2 \\    0 & 0      & 1      & c_3    \end{array} \right]$$

- **Elementary Row Operations That Preserve Solution Sets**:
  1. **Swapping:** Interchanging any two rows ($R_i \leftrightarrow R_j$).
  2. **Scaling:** Multiplying a row by a non-zero scalar ($k R_i \to R_i$).
  3. **Replacement:** Adding a scalar multiple of one row to another row ($R_i + k R_j \to R_i$).

- **Rank & Solution Matrix Criteria**:

| $\text{Rank}(A)$ | $\text{Rank}(A \mid b)$ | System Type | Solution Status |
| :---: | :---: | :--- | :--- |
| $n$ | $n$ | Consistent & Independent | **Unique Solution** |
| $<\ n$ | $<\ n$ | Consistent & Dependent | **Infinitely Many Solutions** |
| $\text{Rank}(A)$ | $<\ \text{Rank}(A \mid b)$ | Inconsistent | **No Solutions** |

---

## 🎯 Technical Skills Architecture

### 📊 Linear Algebra Theory & Rank Mechanics
- **Matrix Rank Evaluation:** Determining row/column ranks to identify redundant equations and measure actual system dimensionality.
- **Gaussian Elimination Logic:** Executing systematic forward elimination to convert matrices into clean triangular shapes for back-substitution.
- **Consistency Analysis:** Assessing augmented matrix criteria to predict whether a linear model has a solution before solving.

### 🤖 Applied Python & NumPy Engineering
- **Augmented Matrix Manipulation:** Combining coefficient matrices and target vectors via `np.hstack()` to construct system augmented arrays.
- **Custom Algorithm Programming:** Writing Python loops and conditional statements to automate row operations, pivot selections, and back-substitution.
- **Numerical Validation:** Cross-checking custom elimination outputs against built-in solvers like `np.linalg.solve()`.

---

## 🛠️ Production Tech Stack & Ecosystem

| Mathematical Concept | Programming Library | Algorithm Focus | Interactive Environment |
| :---: | :---: | :---: | :---: |
| ![Linear Algebra](https://img.shields.io/badge/Row_Operations-REF_%26_RREF-blue?style=flat) | ![NumPy](https://img.shields.io/badge/NumPy-Matrix_Slicing_&_Stacking-013243?style=flat&logo=numpy&logoColor=white) | ![Algorithms](https://img.shields.io/badge/Gaussian-Elimination_%26_Rank-orange?style=flat) | ![Jupyter](https://img.shields.io/badge/Jupyter-Interactive_Labs-FA0F00?style=flat&logo=jupyter&logoColor=white) |
