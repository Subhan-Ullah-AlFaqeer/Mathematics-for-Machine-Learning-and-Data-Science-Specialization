<div align="center">
  
# 🚀 Mathematics for Machine Learning and Data Science Specialization

[![DeepLearning.AI Specialization](https://img.shields.io/badge/Certification-DeepLearning.AI%20Math-blue?style=for-the-badge&logo=deeplearningdotai)](https://coursera.org/share/cf397cd31f8b7a904442cfd4f5d4f1b1)
[![Status](https://img.shields.io/badge/Progress-03%20Courses%20Complete-success?style=for-the-badge)](https://coursera.org/share/94656839e32b3cf49290dc51f47605a9)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/subhan-ullah-alfaqeer)

---
</div>

# 📊 Course 3: Probability & Statistics for Machine Learning & Data Science

Welcome to **Course 3** of the **Mathematics for Machine Learning and Data Science Specialization**, created by DeepLearning.AI and taught by Luis Serrano! This foundational course establishes the core probability and inferential statistics principles that power data-driven machine learning models. You will bridge abstract probabilistic theory with hands-on implementation—moving from exploratory data analysis (EDA) and Bayes' theorem to univariate/multivariate distributions, covariance matrices, the Central Limit Theorem, Maximum Likelihood Estimation (MLE), Bayesian Maximum A Posteriori (MAP) estimation, confidence intervals, and hypothesis testing (including A/B testing).

Throughout this course, you will write production-grade Python code utilizing **Pandas**, **NumPy**, **SciPy**, and **Matplotlib** / **Seaborn** to perform exploratory data analysis, run stochastic Monte Carlo simulations, fit linear regression models, compute confidence intervals, and execute statistical hypothesis tests.

---

## 📝 Core Technical Objectives
- **Probability Foundations & Bayes' Theorem:** Calculating sample spaces, conditional probabilities, and joint events. Applying Bayes' theorem to update prior beliefs with incoming evidence:
  - **Bayes' Formula:** $P(A \mid B) = \frac{P(B \mid A)P(A)}{P(B)}$

- **Multi-Variable Distributions & Covariance:** Analyzing univariate and multi-variable probability distributions, joint/marginal/conditional probabilities, expectation, variance, skewness, kurtosis, covariance matrices, and correlation coefficients ($\rho_{XY}$).

- **Sampling Theory, MLE & Regularization:** Applying the Law of Large Numbers and the Central Limit Theorem (CLT) to understand sample distribution convergence. Deriving Maximum Likelihood Estimators (MLE) and incorporating prior beliefs using Bayesian Maximum A Posteriori (MAP) estimation connected to L1/L2 regularization.

- **Confidence Intervals & Hypothesis Testing:** Constructing interval estimates, formulating null/alternative hypotheses, controlling Type I ($\alpha$) and Type II ($\beta$) errors, computing $p$-values, performing $t$-tests, and evaluating digital product variants via A/B testing.

---

## 🧪 Course Architecture & Module Matrix

This course is structured into 4 sequential modules taking you from probability fundamentals to inferential statistics, estimation, and hypothesis testing:

| Module / Directory | Operational Focus & Technical Topics | Key Notebooks & Deliverables |
| :--- | :--- | :--- |
| **[01_Week](./01_Week)** | **Probability and Probability Distributions**: Exploratory data analysis with Pandas, probability axioms, permutations/combinations, conditional probability, Bayes' theorem, and classic probability paradoxes (Birthday problem, Monty Hall). | • `C3_W1_Assignment.ipynb`<br>• `C3_W1_Lab_1_Birthday_Problems.ipynb`<br>• `C3_W1_Lab_2_Monty_Hall.ipynb`<br>• `C3_W1_Rideshare_Project_Week1.ipynb`<br>• `C3_W1_intro-to-pandas-world-happiness.ipynb` |
| **[02_Week](./02_Week)** | **Describing Probability Distributions & Multi-Variable Probability**: Summary statistics (mean, variance, skewness, kurtosis), joint/marginal/conditional distributions, covariance matrices, correlation coefficients, and multivariate Gaussians. | • `C3_W2_Assignment.ipynb`<br>• `C3_W2_Lab_2_Dice_Simulations.ipynb`<br>• `C3_W2_ugl_datasets.ipynb`<br>• `Rideshare_Project_Week2.ipynb` |
| **[03_Week](./03_Week)** | **Sampling, Point Estimation, and Bayesian Statistics**: Population vs. sample, Law of Large Numbers, Central Limit Theorem (CLT), Point Estimation, Maximum Likelihood Estimation (MLE), Regularization, and Bayesian Statistics (MAP). | • `C3_W3_Assignment.ipynb`<br>• `C3_W3_Lab_1_Central_Limit_Theorem.ipynb`<br>• `linear-regression-world-happiness.ipynb` |
| **[04_Week](./04_Week)** | **Confidence Intervals and Hypothesis Testing**: Interval estimation, confidence intervals, hypothesis formulation ($H_0 / H_1$), Type I/II errors, $p$-values, $t$-tests (one-sample, two-sample, paired), and A/B testing applications. | • `C3_W4_Assignment.ipynb` |

---

## 💡 Visual Pipeline Reference

The unified probabilistic and inferential pipeline governing Course 3:

- **Core Statistical Progression**:

$$\begin{aligned}   \text{Bayes' Rule: } &P(A \mid B) = \frac{P(B \mid A)P(A)}{P(B)} \\   \text{Central Limit Theorem: } &Z = \frac{\bar{X} - \mu}{\sigma / \sqrt{n}} \xrightarrow{d} \mathcal{N}(0, 1) \\   \text{Maximum Likelihood: } &\hat{\theta}_{\text{MLE}} = \arg\max_{\theta} \sum_{i=1}^n \ln P(x_i \mid \theta) \\   \text{Confidence Interval: } &\bar{X} \pm t_{\alpha/2, n-1} \left( \frac{s}{\sqrt{n}} \right)   \end{aligned}$$

- **Core Probability & Statistics Concepts & Machine Learning Mapping**:

| Statistical Concept | Mathematical Expression | Machine Learning / Data Science Application |
| :--- | :--- | :--- |
| **Conditional Probability** | $P(A \mid B) = \frac{P(A \cap B)}{P(B)}$ | Naive Bayes classification, updating model beliefs |
| **Covariance Matrix** | $\Sigma_{ij} = \text{Cov}(X_i, X_j)$ | Multivariate Gaussian modeling, feature dependency analysis |
| **Maximum Likelihood (MLE)** | $\arg\max_{\theta} \sum \ln P(x_i \mid \theta)$ | Logistic regression optimization, neural network loss functions |
| **Confidence Interval / $t$-Test** | $\bar{X} \pm t \cdot \frac{s}{\sqrt{n}}$ | Evaluating model performance uncertainty, A/B testing variants |

---

## 🎯 Technical Skills Architecture

### 📊 Probability & Inferential Statistics Theory
- **Probabilistic Reasoning:** Applying Bayes' theorem and conditional probability rules to model uncertainty in data.
- **Distribution Analysis:** Characterizing uni- and multi-variable datasets using moments, covariance matrices, and multivariate Gaussian properties.
- **Statistical Inference:** Leveraging the Central Limit Theorem, MLE, MAP, confidence intervals, and hypothesis tests to make rigorous data-driven conclusions.

### 🤖 Applied Python & Data Science Engineering
- **Pandas Data wrangling:** Cleaning, filtering, and aggregating tabular datasets to perform exploratory data analysis.
- **Stochastic Simulations:** Running Monte Carlo experiments and simulating random distributions using NumPy.
- **Statistical Solvers:** Executing hypothesis tests, computing confidence intervals, and evaluating A/B testing experiments using SciPy.

---

## 🛠️ Production Tech Stack & Ecosystem

| Mathematical Framework | Data Analytics Libraries | Statistical & Simulation Tools | Interactive Environment |
| :---: | :---: | :---: | :---: |
| ![Probability](https://img.shields.io/badge/Probability_%26_Stats-Theory-blue?style=flat) | ![Pandas & NumPy](https://img.shields.io/badge/Pandas_%26_NumPy-Data_Manipulation-013243?style=flat&logo=numpy&logoColor=white) | ![SciPy & Seaborn](https://img.shields.io/badge/SciPy_%26_Seaborn-Hypothesis_Solvers-3776AB?style=flat&logo=python&logoColor=white) | ![Jupyter](https://img.shields.io/badge/Jupyter-Interactive_Labs-FA0F00?style=flat&logo=jupyter&logoColor=white) |



---
## 🚀 Professional Credentials

Upon the successful completion of this rigorous engineering track, I have earned the following industry-recognized credentials:

🎓 **Coursera Professional Certificate Verified** 

<div align="center">


| **Official Certificate** |
| :---: |
| <a href="https://coursera.org/share/94656839e32b3cf49290dc51f47605a9"><img src="../certificates/003 Coursera Probability & Statistics for Machine Learning & Data Science-1.png" width="580" alt="View Certificate"></a> |
| [🛡️ Verify on Coursera](https://coursera.org/share/94656839e32b3cf49290dc51f47605a9) |


</div> 
