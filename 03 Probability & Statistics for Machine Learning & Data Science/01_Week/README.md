# 🎲 Course 3, Week 1: Probability and Probability Distributions

Welcome to **Week 1** of **Probability & Statistics for Machine Learning & Data Science** (Course 3 of the DeepLearning.AI Mathematics for Machine Learning and Data Science Specialization)! This module introduces the fundamental principles of probability theory and data handling. You will explore exploratory data analysis using Pandas, calculate empirical and theoretical probabilities, investigate classic paradoxes like the Birthday Problem and Monty Hall, apply Bayes' theorem, and analyze discrete/continuous probability distributions.

---

## 📝 Core Technical Objectives
- **Exploratory Data Analysis (EDA) with Pandas:** Loading, cleaning, and aggregating structured datasets (e.g., World Happiness report and rideshare analytics) to uncover statistical insights.

- **Probability Fundamentals & Combinatorics:** Calculating sample spaces, event probabilities, permutations, and combinations. Exploring conditional probability and independent events:
  - **Conditional Probability:** $P(A \mid B) = \frac{P(A \cap B)}{P(B)}$

- **Bayes' Theorem & Diagnostic Testing:** Reversing conditional probabilities to update prior beliefs given new evidence:
  - **Bayes' Formula:** $P(A \mid B) = \frac{P(B \mid A)P(A)}{P(B)}$

- **Probability Distributions:** Defining discrete and continuous random variables, probability mass functions (PMF), cumulative distribution functions (CDF), and expectation/variance metrics.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core video lectures, keynote notes, interactive labs, and practical data science assignments are mapped directly to their operational focus:

| Asset / Deliverable | Operational Focus |
| :--- | :--- |
| **[Keynote Slides](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/01_Week/Lecture%20Files/Week%201%20%20-%20Probability%20and%20Probability%20Distribution%20Keynote.pdf)** | Formal visual reference covering probability axioms, conditional probability proofs, Bayes' theorem derivations, and distribution properties. |
| **[Pandas World Happiness Lab (`C3_W1_intro-to-pandas-world-happiness.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/01_Week/Labs/C3_W1_intro-to-pandas-world-happiness.ipynb)** | Hands-on data manipulation in Python using Pandas for loading, filtering, and summarizing statistical indicators. |
| **[Birthday Problems Lab (`C3_W1_Lab_1_Birthday_Problems.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/01_Week/Labs/C3_W1_Lab_1_Birthday_Problems.ipynb)** | Simulating and calculating collision probabilities for shared birthdays in groups to understand counter-intuitive probability laws. |
| **[Monty Hall Paradox Lab (`C3_W1_Lab_2_Monty_Hall.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20and%20Data%20Science/01_Week/Labs/C3_W1_Lab_2_Monty_Hall.ipynb)** | Coding simulations for the Monty Hall game show to demonstrate conditional probability shifts upon door revelation. |
| **[Rideshare Project Week 1 (`C3_W1_Rideshare_Project_Week1.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/01_Week/Labs/C3_W1_Rideshare_Project_Week1.ipynb)** | Applied data science mini-project analyzing rideshare operational patterns and probabilistic distributions using Python. |
| **[Probability Assignment (`C3_W1_Assignment.ipynb`)](./03%20Probability%20&%20Statistics%20for%20Machine%20Learning%20&%20Data%20Science/01_Week/Labs/C3_W1_Assignment.ipynb)** | End-to-end coding assignment solving probability calculations, Bayes' theorem applications, and distribution problems. |

---

## 💡 Visual Pipeline Reference

The foundational probability formulations governing Week 1:

- **Conditional Probability & Multiplication Rule**:

  $$P(A \cap B) = P(A \mid B)P(B) = P(B \mid A)P(A)$$

- **Law of Total Probability**:

  $$P(B) = \sum_{i} P(B \mid A_i)P(A_i)$$

- **Bayes' Theorem Expansion**:

  $$P(A_i \mid B) = \frac{P(B \mid A_i)P(A_i)}{\sum_{j} P(B \mid A_j)P(A_j)}$$

---

## 🎯 Technical Skills Architecture

### 📊 Probability Theory & Data Analytics
- **Conditional Reasoning:** Evaluating how prior probabilities update when conditioned on dependent events or observed evidence.
- **Paradox Resolution:** Analyzing counter-intuitive problems (Birthday paradox, Monty Hall) using formal probability rules.
- **Exploratory Data Analysis:** Extracting statistical metrics, distributions, and trends from tabular datasets.

### 🤖 Applied Python & Data Science Engineering
- **Pandas Manipulation:** Filtering, grouping, and aggregating data frames efficiently in Python.
- **Stochastic Simulation:** Writing Monte Carlo simulations using NumPy and random sampling to estimate empirical probabilities.
- **Data Visualization:** Plotting probability distributions and categorical breakdowns using Matplotlib and Seaborn.

---

## 🛠️ Production Tech Stack & Ecosystem

| Mathematical Framework | Data Manipulation Library | Simulation & Stats Tools | Interactive Environment |
| :---: | :---: | :---: | :---: |
| ![Probability](https://img.shields.io/badge/Probability-Bayes_%26_Rules-blue?style=flat) | ![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=flat&logo=pandas&logoColor=white) | ![NumPy](https://img.shields.io/badge/NumPy_%26_SciPy-Stochastic_Simulation-013243?style=flat&logo=numpy&logoColor=white) | ![Jupyter](https://img.shields.io/badge/Jupyter-Interactive_Labs-FA0F00?style=flat&logo=jupyter&logoColor=white) |
