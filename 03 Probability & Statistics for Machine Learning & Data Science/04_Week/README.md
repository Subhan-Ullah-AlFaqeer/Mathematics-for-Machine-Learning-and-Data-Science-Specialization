```markdown
# 🔬 Interval Estimation, Hypothesis Testing & A/B Testing

Welcome to this module covering the core inferential statistics and experimental evaluation methods in data science: **Confidence Intervals, Null Hypothesis Significance Testing (NHST), Parametric t-Tests, and A/B Testing Experiments**.

This module bridges sample estimates and decision-making under uncertainty, taking you from interval estimation and margin of error calculations to evaluating statistical significance, controlling decision errors, and evaluating real-world A/B testing scenarios.

---

## 📝 Core Technical Objectives
* **Interval Estimation & Margin of Error:** Calculating confidence intervals for population means and proportions across known and unknown standard deviation ($\sigma$) scenarios.
* **Hypothesis Testing Frameworks:** Formulating Null ($H_0$) and Alternative ($H_1$) hypotheses, computing test statistics, evaluating critical regions, and determining $p$-values.
* **Statistical Decision Errors & Power:** Quantifying Type I error ($\alpha$), Type II error ($\beta$), and statistical power ($1 - \beta$) in directional and two-tailed tests.
* **Parametric Testing & A/B Evaluation:** Conducting Student's t-tests, Welch's two-sample t-tests, paired t-tests, proportion tests, and executing controlled A/B testing experiments.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core video lectures, interactive tools, hands-on labs, and graded assignments are mapped directly to their targeted analytical focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **Interval Estimation & Sample Size Planning** | Video series and interactive tool exploring confidence levels, margins of error, Student's t-distributions, and required sample size estimations. |
| **Hypothesis Testing & Statistical Errors** | Video series covering $p$-value interpretations, Type I/II errors, test power, one-tailed/two-tailed setups, and critical value boundaries. |
| **Parametric Tests & Proportions** | Video series and readings detailing one-sample t-tests, two-sample t-tests, paired t-tests, and proportion hypothesis tests. |
| **Exploratory Data Analysis Lab** | Hands-on lab applying confidence interval calculations and hypothesis testing workflows to empirical datasets. |
| **A/B Testing Programming Project** | Graded programming assignment designing, executing, and statistically evaluating an end-to-end A/B experiment for feature impact assessment. |

---

## 💡 Visual Pipeline Reference

The hypothesis testing and experimental evaluation workflow implemented across this module:

* **Experimental Design & Setup** ➔ Define $H_0$ vs. $H_1$ ➔ Select significance threshold ($\alpha = 0.05$) ➔ Estimate sample size $n$.
* **Sample Data Ingestion** ➔ Calculate sample mean $\bar{X}$ and standard deviation $s$ ➔ Compute **Standard Error** $SE = \frac{s}{\sqrt{n}}$.
* **Test Statistic Computation** ➔ Derive score $t = \frac{\bar{X} - \mu_0}{SE}$ based on degrees of freedom $df = n - 1$.
* **Inference & Decision Rule** ➔ Calculate **$p$-value** ➔ Reject $H_0$ if $p \le \alpha$ ➔ Report confidence interval $\bar{X} \pm t_{\alpha/2} \cdot SE$.

---

## 🎯 Technical Skills Architecture

### 📊 Inferential Statistics & Experimental Design
* **Confidence Interval Estimation:** Constructing bounded intervals for population metrics under varying sample size constraints.
* **Statistical Error Control:** Balancing false positive rates ($\alpha$) and false negative rates ($\beta$) while optimizing test power.
* **Parametric Significance Testing:** Selecting appropriate test models (Z-test vs. t-test, independent vs. paired samples) based on data assumptions.

### 🤖 Applied Machine Learning & Product Analytics
* **A/B Experimentation:** Designing randomized controlled experiments to measure conversion lift and feature impact.
* **Proportion & Metric Comparison:** Evaluating click-through rates (CTR) and conversion metrics using z-tests for proportions.
* **Data-Driven Decision Making:** Translating statistical $p$-values and effect sizes into actionable product deployment decisions.

---

## 🛠️ Production Tech Stack & Ecosystem

| Core Mathematics | Data Analysis | Interactive Environments | Algorithm Architecture |
| :---: | :---: | :---: | :---: |
| ![Statistics](https://img.shields.io/badge/Mathematics-Inferential_Statistics-blue?style=flat&logo=sympy&logoColor=white) | ![SciPy](https://img.shields.io/badge/SciPy-Hypothesis_Testing-8CAAE6?style=flat&logo=scipy&logoColor=white) | ![Jupyter](https://img.shields.io/badge/Jupyter-Interactive_Labs-FA0F00?style=flat&logo=jupyter&logoColor=white) | ![Python](https://img.shields.io/badge/Python-A/B_Testing-3670A0?style=flat&logo=python&logoColor=ffdd54) |

```
