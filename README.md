# Task 16 — Hypothesis Testing & A/B Tests

## 📌 Project Overview

This project performs hypothesis testing and an A/B-style comparison using the Superstore sales dataset.

The analysis compares the average **Sales** between:

- **Group A:** Consumer
- **Group B:** Corporate

The objective is to determine whether the difference in average Sales is statistically significant.

## 🎯 Objectives

- Formulate null and alternative hypotheses
- Compare Consumer and Corporate sales
- Perform an independent two-sample t-test
- Calculate Cohen's d effect size
- Calculate a 95% confidence interval
- Estimate sample size and statistical power
- Interpret statistical results
- Provide a business recommendation

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Google Colab
- Jupyter Notebook

## 📊 Statistical Method

**Test:** Welch's Independent Two-Sample t-test

**Significance Level:** α = 0.05

### Hypotheses

**H₀:** The average Sales of Consumer and Corporate customers are equal.

**H₁:** The average Sales of Consumer and Corporate customers are different.

## 📈 Analysis Performed

1. Data loading and validation
2. Missing-value checking
3. Customer-segment grouping
4. Descriptive statistics
5. Sales distribution visualization
6. Cohen's d effect-size calculation
7. Sample-size/power analysis
8. Welch's t-test
9. 95% confidence interval
10. Statistical decision
11. Business recommendation

## 💡 Key Insight

The final statistical decision is based on the **p-value**. Cohen's d and the confidence interval are also used to understand the
