# 📊 Course 3, Week 2: Describing Probability Distributions and Multi-Variable Probability

Welcome to **Week 2** of **Probability & Statistics for Machine Learning & Data Science** (Course 3 of the DeepLearning.AI Mathematics for Machine Learning and Data Science Specialization)! This module explores univariate summary statistics and multi-variable probability distributions. You will transition from single random variables to joint, marginal, and conditional distributions, analyze covariance matrices, investigate correlation coefficients, explore multivariate Gaussian distributions, and build loaded dice simulation models in Python.

---

## 📝 Core Technical Objectives
- **Univariate Summary Statistics:** Calculating measures of central tendency (mean, median, mode), dispersion (variance, standard deviation), and distribution shape (skewness and kurtosis) using expected value operators.

- **Joint, Marginal & Conditional Distributions:** Extending probability analysis to multiple random variables. Defining joint distributions $P(X=x, Y=y)$, extracting marginal distributions by summing/integrating out variables, and computing conditional distributions $P(X \mid Y=y)$.

- **Covariance, Correlation & Multivariate Gaussians:** Measuring linear association between variables via covariance and standardized correlation coefficients $\rho_{XY}$. Assembling covariances into covariance matrices and exploring the multi-dimensional properties of Multivariate Gaussian distributions.

- **Loaded Dice Simulations & Exploratory Data Analysis:** Simulating stochastic game mechanics with NumPy and visualizing statistical distributions across real-world datasets.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core video lectures, keynote notes, interactive labs, and the primary loaded dice programming assignment are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **[Keynote Slides](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/02_Week/Lecture%20Files/Week%202%20%20-%20Distributions%20and%20Probability%20Distribution%20Keynote.pdf)** | Formal visual reference covering expectation, variance, covariance formulas, joint distribution tables, and multivariate Gaussian probability density functions. |
| **[Summary Statistics & Data Visualization Lab](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/02_Week/Labs/)** | Hands-on Python implementation computing summary statistics (mean, variance, skewness, kurtosis) and plotting histograms and box plots. |
| **[Simulating Dice Rolls with NumPy Lab (`C3_W2_Lab_2_Dice_Simulations.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/02_Week/Labs/C3_W2_Lab_2_Dice_Simulations.ipynb)** | Helper tutorial demonstrating how to use NumPy random number generators to simulate discrete probability distributions for dice throws. |
| **[Rideshare Project Week 2 (`Rideshare_Project_Week2.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/02_Week/Labs/Rideshare_Project_Week2.ipynb)** | Applied data science project analyzing multi-variable relationships, correlations, and distributions within rideshare data. |
| **[Loaded Dice Assignment (`C3_W2_Assignment.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/02_Week/Labs/C3_W2_Assignment.ipynb)** | End-to-end coding assignment building and evaluating statistical models for loaded dice using empirical frequencies and probability distributions. |

---

## 💡 Visual Pipeline Reference

The foundational statistical and multi-variable formulas governing Week 2:

- **Expected Value & Variance**:

  $$E[X] = \sum x P(x), \quad \text{Var}(X) = E[(X - E[X])^2] = E[X^2] - (E[X])^2$$

- **Covariance & Correlation Coefficient**:

  $$\text{Cov}(X, Y) = E[(X - E[X])(Y - E[Y])], \quad \rho_{XY} = \frac{\text{Cov}(X, Y)}{\sigma_X \sigma_Y}$$

- **Marginal Distribution from Joint Distribution**:

  $$P(X = x) = \sum_{y} P(X = x, Y = y)$$

---

## 🎯 Technical Skills Architecture

### 📊 Probability Theory & Multi-Variable Statistics
- **Distribution Analysis:** Characterizing data spreads using variance, standard deviation, skewness, and kurtosis.
- **Multi-Variable Modeling:** Computing joint, marginal, and conditional probabilities to analyze dependencies between features.
- **Covariance & Correlation:** Evaluating linear relationships and variance structures across multi-dimensional datasets.

### 🤖 Applied Python & Data Science Engineering
- **NumPy Stochastic Simulations:** Generating weighted random samples and simulating discrete probability distributions.
- **Pandas Data Summarization:** Computing descriptive statistics and grouping multi-variable datasets efficiently.
- **Statistical Visualization:** Plotting multi-variable distributions, scatter plots, and correlation heatmaps using Matplotlib and Seaborn.

---

## 🛠️ Production Tech Stack & Ecosystem

| Mathematical Framework | Data Analytics Libraries | Simulation Tools | Interactive Environment |
| :---: | :---: | :---: | :---: |
| ![Statistics](https://img.shields.io/badge/Statistics-Covariance_%26_Joint_Distributions-blue?style=flat) | ![Pandas & NumPy](https://img.shields.io/badge/Pandas_%26_NumPy-Summary_Stats-013243?style=flat&logo=numpy&logoColor=white) | ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-3776AB?style=flat&logo=python&logoColor=white) | ![Jupyter](https://img.shields.io/badge/Jupyter-Interactive_Labs-FA0F00?style=flat&logo=jupyter&logoColor=white) |
