```markdown
# 🎲 Probability Foundations, Bayes Theorem & Naive Bayes

Welcome to this module covering the core probability and statistical foundations of machine learning: **Probability Rules, Bayes Theorem, Probability Distributions, and the Naive Bayes Classifier**.

This module bridges foundational probability theory and practical machine learning, taking you from basic event rules and conditional probabilities to continuous probability distributions, exploratory data analysis with Pandas, and building a Naive Bayes classifier from scratch.

---

## 📝 Core Technical Objectives
* **Probability Rules & Independence:** Calculating event probabilities, complements, joint/disjoint sums, conditional probabilities, and independence.
* **Bayesian Inference & Naive Bayes:** Applying Bayes Theorem ($P(A|B) = \frac{P(B|A)P(A)}{P(B)}$) to spam filtering and building the probabilistic Naive Bayes classifier.
* **Discrete & Continuous Distributions:** Modeling probability mass functions (PMF), probability density functions (PDF), cumulative distribution functions (CDF), and standard distributions (Binomial, Bernoulli, Uniform, Normal, Chi-Squared).
* **Exploratory Data Analysis & Sampling:** Sampling from theoretical distributions and exploring real-world data structures using Pandas.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core video lectures, interactive tools, hands-on labs, and graded assignments are mapped directly to their targeted analytical focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **Probability Foundations & Birthday Problems** | Video series, interactive simulation, and hands-on lab exploring event probability, joint/disjoint rules, and birthday paradox edge cases. |
| **Bayes Theorem & Naive Bayes Model** | Video series and hands-on Monty Hall lab deriving prior/posterior relationships and applying Naive Bayes to spam detection. |
| **Probability Distributions & Sampling** | Video series, interactive PMF/PDF/CDF visual tool, and sampling techniques across discrete and continuous distributions. |
| **Exploratory Data Analysis (EDA)** | Two hands-on labs using Pandas to load, clean, transform, sample, and analyze datasets. |
| **Naive Bayes Implementation** | Programming assignment building a complete Naive Bayes classification model from scratch for real-world predictions. |

---

## 💡 Visual Pipeline Reference

The probabilistic workflow implemented across this module:

* **Event Probability Definition** ➔ Calculate sample space $S$ ➔ Derive **Joint & Conditional Probabilities** $P(A \cap B)$ and $P(A|B)$.
* **Bayesian Inversion** ➔ Update **Prior Belief** $P(\text{Spam})$ using **Likelihood** $P(\text{Words}|\text{Spam})$ to compute **Posterior Probability** $P(\text{Spam}|\text{Words})$.
* **Distribution Modeling** ➔ Fit data to **PMF/PDF Functions** (Bernoulli, Binomial, Uniform, Normal) ➔ Evaluate **CDF Thresholds**.
* **Naive Bayes Classification** ➔ Apply conditional independence assumption ➔ Select class $\hat{y} = \arg\max_y P(y) \prod_{i=1}^n P(x_i|y)$.

---

## 🎯 Technical Skills Architecture

### 📊 Probability & Mathematical Statistics
* **Conditional Probability & Bayes Theorem:** Inverting conditional dependencies and deriving posterior distributions from empirical data.
* **Parametric Distributions:** Characterizing discrete and continuous probability mass, density, and cumulative distribution functions.
* **Statistical Sampling:** Generating representative samples from theoretical distributions for empirical estimation.

### 🤖 Applied Machine Learning Engineering
* **Naive Bayes Classifier:** Implementing feature independence assumptions for text classification and spam detection pipelines.
* **Exploratory Data Analysis:** Utilizing Pandas for data loading, filtering, aggregation, and structural data profiling.
* **Probabilistic Modeling:** Mapping real-world uncertainties into formal mathematical decision boundaries.

---

## 🛠️ Production Tech Stack & Ecosystem

| Core Mathematics | Data Analysis | Interactive Environments | Algorithm Architecture |
| :---: | :---: | :---: | :---: |
| ![Probability](https://img.shields.io/badge/Mathematics-Probability_%26_Bayes-blue?style=flat&logo=sympy&logoColor=white) | ![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=flat&logo=pandas&logoColor=white) | ![Jupyter](https://img.shields.io/badge/Jupyter-Interactive_Labs-FA0F00?style=flat&logo=jupyter&logoColor=white) | ![Python](https://img.shields.io/badge/Python-Naive_Bayes-3670A0?style=flat&logo=python&logoColor=ffdd54) |

```
