# 📉 Course 3, Week 3: Sampling, Point Estimation, and Bayesian Statistics

Welcome to **Week 3** of **Probability & Statistics for Machine Learning & Data Science** (Course 3 of the DeepLearning.AI Mathematics for Machine Learning and Data Science Specialization)! This module transitions your focus from pure probability to inferential statistics. You will explore populations versus samples, the Law of Large Numbers, the Central Limit Theorem (CLT), point estimation, Maximum Likelihood Estimation (MLE), linear regression modeling, regularization, and Bayesian statistics including Maximum A Posteriori (MAP) estimation.

---

## 📝 Core Technical Objectives
- **Sampling Theory & The Central Limit Theorem (CLT):** Understanding how sample statistics approximate population parameters. Demonstrating that the distribution of sample means approaches a normal distribution regardless of the underlying population distribution as sample size $n$ increases:

  $$\bar{X} \sim \mathcal{N}\left(\mu, \frac{\sigma^2}{n}\right)$$

- **Point Estimation & Maximum Likelihood Estimation (MLE):** Finding point estimates that maximize the likelihood function of observed data. Deriving MLE parameters for Bernoulli trials, Gaussian populations, and linear regression coefficients.

- **Regularization & Overfitting Prevention:** Adding penalty terms (L1/Lasso, L2/Ridge) to loss functions to prevent model overfitting by discouraging overly large parameter weights.

- **Bayesian Statistics & Maximum A Posteriori (MAP):** Incorporating prior beliefs into statistical inference. Updating priors with likelihood data to compute posterior distributions, and connecting MAP to regularization techniques.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core video lectures, keynote notes, interactive CLT/MLE labs, and exploratory linear regression assignments are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **[Lecture Notes & Slides](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/03_Week/Lecture%20Files/Week%203%20-%20Sampling%20and%20Point%20Estimation%20note.pdf)** | Formal visual reference covering Law of Large Numbers proofs, Central Limit Theorem derivations, MLE formulas, regularization mechanics, and Bayesian update equations. |
| **[Central Limit Theorem Lab (`C3_W3_Lab_1_Central_Limit_Theorem.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/03_Week/Labs/C3_W3_Lab_1_Central_Limit_Theorem.ipynb)** | Hands-on Python simulation sampling from various non-normal distributions and visualizing the convergence of sample means to a normal distribution. |
| **[Linear Regression World Happiness Lab (`linear-regression-world-happiness.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/03_Week/Labs/linear-regression-world-happiness.ipynb)** | Applied exploratory data analysis and linear regression modeling using real-world data to practice point estimation and fitting. |
| **[Probability & Statistics Assignment (`C3_W3_Assignment.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/03_Week/Labs/)** | End-to-end coding assignment implementing MLE parameter estimations, likelihood calculations, and Bayesian updating problems. |

---

## 💡 Visual Pipeline Reference

The foundational statistical and inferential equations governing Week 3:

- **Central Limit Theorem (Sample Mean Normal Approximation)**:

  $$Z = \frac{\bar{X} - \mu}{\sigma / \sqrt{n}} \xrightarrow{d} \mathcal{N}(0, 1)$$

- **Maximum Likelihood Estimation (Log-Likelihood Maximization)**:

  $$\hat{\theta}_{\text{MLE}} = \arg\max_{\theta} \sum_{i=1}^n \ln P(x_i \mid \theta)$$

- **Bayes' Theorem for MAP Estimation**:

  $$\theta_{\text{MAP}} = \arg\max_{\theta} P(\theta \mid X) = \arg\max_{\theta} \left[ P(X \mid \theta) P(\theta) \right]$$

---

## 🎯 Technical Skills Architecture

### 📊 Inferential Statistics & Estimation Theory
- **Sampling Diagnostics:** Evaluating population parameters from sample subsets using Law of Large Numbers and Central Limit Theorem principles.
- **Likelihood Optimization:** Deriving analytical and numerical MLE estimators for discrete and continuous distributions.
- **Bayesian Updating:** Combining prior distributions with observed likelihoods to compute posterior parameter estimates.

### 🤖 Applied Python & Statistical Modeling
- **Monte Carlo Simulations:** Programming sample distribution simulations across diverse statistical populations using NumPy.
- **Linear Regression Fitting:** Building exploratory regression models and analyzing parameter estimates in Python.
- **Regularization Analysis:** Applying L1/L2 penalty mechanics to constrain model complexity and improve generalization.

---

## 🛠️ Production Tech Stack & Ecosystem

| Mathematical Framework | Statistical & ML Libraries | Visualization Tools | Interactive Environment |
| :---: | :---: | :---: | :---: |
| ![Statistics](https://img.shields.io/badge/Inferential_Stats-MLE_%26_Bayesian-blue?style=flat) | ![NumPy & SciPy](https://img.shields.io/badge/NumPy_%26_SciPy-Optimization_&_Sampling-013243?style=flat&logo=numpy&logoColor=white) | ![Matplotlib](https://img.shields.io/badge/Matplotlib-CLT_Distributions-11557c?style=flat) | ![Jupyter](https://img.shields.io/badge/Jupyter-Interactive_Labs-FA0F00?style=flat&logo=jupyter&logoColor=white) |
