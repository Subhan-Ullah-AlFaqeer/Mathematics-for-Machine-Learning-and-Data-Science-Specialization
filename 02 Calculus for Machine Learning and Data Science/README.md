<div align="center">
  
# 🚀 Mathematics for Machine Learning and Data Science Specialization



[![DeepLearning.AI Specialization](https://img.shields.io/badge/Certification-DeepLearning.AI%20Math-blue?style=for-the-badge&logo=deeplearningdotai)](https://coursera.org/share/cf397cd31f8b7a904442cfd4f5d4f1b1)
[![Status](https://img.shields.io/badge/Progress-02%20Course%20Complete-success?style=for-the-badge)](https://coursera.org/share/3c787da9283b77ef3be0960e7d596e4f)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/subhan-ullah-alfaqeer)

---
</div>

# 📈 Course 2: Calculus for Machine Learning and Data Science

Welcome to **Course 2** of the **Mathematics for Machine Learning and Data Science Specialization**, created by DeepLearning.AI and taught by Luis Serrano! This foundational course establishes the core calculus principles that power modern machine learning models and neural network training loops. You will bridge abstract mathematical theory with hands-on implementation—moving from geometric slopes and analytical differentiation rules to first-order gradient descent, partial derivatives, multi-layer backpropagation, second-order Hessians, and Newton's optimization method.

Throughout this course, you will write production-grade Python code utilizing **NumPy**, **SymPy**, and **Matplotlib** to compute symbolic derivatives, visualize loss contour surfaces, program gradient descent optimizers from scratch, train perceptrons for regression and classification, and build a two-layer neural network with backpropagation.

---

## 📝 Core Technical Objectives
- **Analytical Differentiation & Calculus Rules:** Calculating derivatives of polynomials, exponentials ($e^x$), logarithms ($\ln x$), and trigonometric functions. Applying fundamental calculus rules for composite functions:
  - **Chain Rule:** $\frac{d}{dx} f(g(x)) = f'(g(x)) \cdot g'(x)$

- **First-Order Optimization & Gradient Descent:** Implementing iterative parameter updates to locate cost function minima. Using learning rates $\alpha$ and gradients to guide parameter trajectories across multi-variable cost landscapes:
  - **Single Variable Update:** $w_{t+1} = w_t - \alpha \frac{df}{dw}(w_t)$
  - **Multi-Variable Update:** $w \leftarrow w - \alpha \nabla J(w)$

- **Neural Network Backpropagation & Perceptrons:** Constructing single-neuron perceptrons for regression and binary classification using activation functions like the sigmoid function $\sigma(z) = \frac{1}{1 + e^{-z}}$. Applying the chain rule systematically across layers to compute gradients for backpropagation training loops.

- **Second-Order Derivatives, Hessians & Newton's Method:** Analyzing function curvature and concavity using second-order derivatives ($f''(x)$) and assembling the Hessian matrix $\mathbf{H}$. Accelerating convergence using second-order optimization to jump directly toward critical points:
  - **Newton's Update Rule:** $w_{t+1} = w_t - \mathbf{H}^{-1} \nabla f(w_t)$

---

## 🧪 Course Architecture & Module Matrix

This course is structured into 3 sequential modules taking you from basic derivatives to gradient descent optimization and deep neural network training:

| Module / Directory | Operational Focus & Technical Topics | Key Notebooks & Deliverables |
| :--- | :--- | :--- |
| **[01_Week](./01_Week)** | **Derivatives and Optimization**: Tangent line geometry, common function derivatives (polynomials, exponentials, logs), sum/product/chain rules, symbolic/numerical/automatic differentiation, and cost function minimization. | • `C2_W1_Assignment.ipynb`<br>• `C2_W1_Lab_1_differentiation_in_python.ipynb` |
| **[02_Week](./02_Week)** | **Gradients and Gradient Descent**: Single and multi-variable gradient descent, partial derivatives, learning rate tuning, contour plot optimization, and least squares linear regression. | • `C2_W2_Assignment.ipynb`<br>• `C2_W2_Lab_1_Optimization_Using_Gradient_Descent_in_One_Variable.ipynb`<br>• `C2_W2_Lab_2_Optimization_Using_Gradient_Descent_in_Two_Variables.ipynb` |
| **[03_Week](./03_Week)** | **Optimization in Neural Networks and Newton's Method**: Perceptrons for regression and binary classification, sigmoid activation gradients, backpropagation chain rule, second-order derivatives, Hessian matrices, and Newton's method. | • `C2_W3_Assignment.ipynb`<br>• `C2_W3_Lab_1_Regression_with_Perceptron.ipynb`<br>• `C2_W3_Lab_2_Classification_with_Perceptron.ipynb`<br>• `C2_W3_Lab_3_Optimization_Using_Newtons_Method.ipynb` |

---

## 💡 Visual Pipeline Reference

The unified mathematical progression and optimization workflow governing Course 2:

- **Calculus Foundation to Neural Network Optimization**:

$$\begin{aligned}   \text{Derivative Definition: } &f'(x) = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h} \\   \text{Gradient Descent Update: } &w_{t+1} = w_t - \alpha \nabla J(w_t) \\   \text{Neural Network Backprop: } &\frac{\partial L}{\partial w^{[l]}} = \frac{\partial L}{\partial a^{[l]}} \cdot \frac{\partial a^{[l]}}{\partial z^{[l]}} \cdot \frac{\partial z^{[l]}}{\partial w^{[l]}} \\   \text{Newton's Optimization: } &w_{t+1} = w_t - \mathbf{H}^{-1} \nabla J(w_t)   \end{aligned}$$

- **Core Calculus Concepts & Deep Learning Mapping**:

| Calculus Concept | Mathematical Expression | Machine Learning / Deep Learning Application |
| :--- | :--- | :--- |
| **Derivative / Slope** | $\frac{df}{dx}$ | Measuring rate of cost change, guiding gradient updates |
| **Partial Derivative** | $\frac{\partial J}{\partial w_i}$ | Isolating parameter sensitivities in multi-weight models |
| **Chain Rule** | $\frac{df}{dx} = \frac{df}{dg} \cdot \frac{dg}{dx}$ | Powering backpropagation across multi-layer neural networks |
| **Hessian Matrix** | $\mathbf{H}_{ij} = \frac{\partial^2 J}{\partial w_i \partial w_j}$ | Second-order optimization, analyzing loss landscape curvature |

---

## 🎯 Technical Skills Architecture

### 📊 Calculus Theory & Optimization Dynamics
- **Analytical Differentiation:** Applying sum, product, and chain rules to compute exact gradients of complex loss functions.
- **Gradient Landscape Analysis:** Interpreting contour plots, partial derivatives, and gradient vectors to understand convergence trajectories and learning rate behaviors.
- **Second-Order Curvature:** Analyzing eigenvalues and inverses of Hessian matrices to evaluate local extrema and accelerate convergence using Newton's method.

### 🤖 Applied Python & Deep Learning Engineering
- **Symbolic Math Operations:** Utilizing SymPy and NumPy to compute exact analytical derivatives and numerical approximations in Python.
- **Custom Optimization Implementations:** Programming gradient descent loops and least squares regression models from scratch.
- **Neural Network Backpropagation:** Building and training multi-layer perceptrons and two-layer neural networks using vectorized backpropagation in Python.

---

## 🛠️ Production Tech Stack & Ecosystem

| Mathematical Framework | Core Scientific Libraries | Visualization Tool | Interactive Environment |
| :---: | :---: | :---: | :---: |
| ![Calculus](https://img.shields.io/badge/Calculus-Derivatives_%26_Gradients-blue?style=flat) | ![NumPy](https://img.shields.io/badge/NumPy_%26_SymPy-Symbolic_&_Numerical_Math-013243?style=flat&logo=python&logoColor=white) | ![Matplotlib](https://img.shields.io/badge/Matplotlib-Loss_%26_Contour_Plots-11557c?style=flat) | ![Jupyter](https://img.shields.io/badge/Jupyter-Interactive_Labs-FA0F00?style=flat&logo=jupyter&logoColor=white) |


---
## 🚀 Professional Credentials

Upon the successful completion of this rigorous engineering track, I have earned the following industry-recognized credentials:

🎓 **Coursera Professional Certificate Verified** 

<div align="center">


| **Official Certificate** |
| :---: |
| <a href="https://coursera.org/share/3c787da9283b77ef3be0960e7d596e4f"><img src="../certificates/002 Coursera Calculus for Machine Learning and Data Science-1.png" width="580" alt="View Certificate"></a> |
| [🛡️ Verify on Coursera](https://coursera.org/share/3c787da9283b77ef3be0960e7d596e4f) |


</div>
