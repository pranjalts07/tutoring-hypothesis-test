# 📊 Tutoring Effect Hypothesis Test

![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-Hypothesis%20Testing-blue)
![Project](https://img.shields.io/badge/Project-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Project Overview

This project is a **statistical hypothesis testing study** that examines whether **paid tutoring** has a measurable impact on **students’ final mathematics performance (G3)**.

Using the **UCI Student Performance – Mathematics** dataset, the analysis applies **exploratory data analysis (EDA)**, **visualizations**, and a **two-sample t-test** to compare final grades between students who received paid tutoring and those who did not.

The project is implemented in **R** using **Quarto** for reproducible reporting.

---

## ❓ Research Question

**Do students who receive paid tutoring achieve higher final math grades than students who do not receive tutoring?**

---

## 🧠 Hypotheses

- **Null Hypothesis (H₀):**  
  There is no difference in mean final math grades (G3) between students who receive paid tutoring and those who do not.

- **Alternative Hypothesis (H₁):**  
  Students who receive paid tutoring have a higher mean final math grade than those who do not.

---

## 🧪 Methodology

The analysis follows these steps:

1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
   - Summary statistics  
   - Visualizations (histograms, boxplots)  
3. Assumption checks  
   - Independence  
   - Sample size and approximate normality  
4. Statistical inference using a **Welch Two-Sample t-test**

The Welch t-test was chosen to account for **unequal variances** between groups.

---

## 📈 Key Findings

- Students who received paid tutoring showed a **higher average final math grade (G3)** than students who did not.
- The hypothesis test returned a **statistically significant result**, providing evidence against the null hypothesis.
- Although statistically significant, the observed effect size is **moderate**, suggesting tutoring offers a measurable but limited improvement in performance.

---

## 🗂️ Repository Structure

