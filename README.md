# Tutoring Effect Hypothesis Test

![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-Hypothesis%20Testing-blue)
![Project](https://img.shields.io/badge/Project-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---
##  Research Question

**Do students who receive paid tutoring achieve higher final math grades than students who do not receive tutoring?**

---
## Project Overview

This project is a **statistical hypothesis testing study** examining whether **paid tutoring** is associated with higher **final mathematics performance (G3)** among secondary-school students.

Using the **UCI Student Performance – Mathematics** dataset, the analysis applies **exploratory data analysis (EDA)**, **visualization**, and a **two-sample t-test** to compare the mean final math grades of students who received paid tutoring with those who did not. 

The project is implemented in **R** using **Quarto** for reproducible reporting.
---

## Hypotheses

- **Null Hypothesis (H₀):**  
  There is no difference in mean final math grades (G3) between students who receive paid tutoring and those who do not.

- **Alternative Hypothesis (H₁):**  
  Students who receive paid tutoring have a higher mean final math grade than those who do not.

---

## 🧪 Methodology

The analysis follows a structured statistical workflow:

1. Data cleaning and preprocessing. 
2. Exploratory Data Analysis (EDA).   
3. Assumption checks:  
   - Independence of observations  
   - Normality
4. Statistical inference using a **two-sample t-test** to compare mean final grades between the two independent groups.
5. decision and conclusion.
---

## Key Findings

- Students who received paid tutoring had a **slightly higher mean final math grade** compared to those who did not receive tutoring.
- The two-sample t-test produced a **statistically significant p-value**, providing evidence against the null hypothesis.
- The 95% confidence interval for the mean difference was entirely positive, indicating that the true mean final grade for tutored students is likely higher.
- Despite statistical significance, the **effect size was small**, suggesting that the practical impact of tutoring on final grades is modest.
