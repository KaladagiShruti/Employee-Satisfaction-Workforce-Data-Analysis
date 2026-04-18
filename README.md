# Employee Satisfaction & Workforce Data Analysis

> **MSc Data Science | Kingston University**
> Individual assignment | My work throughout

---

## Overview

This project analyses an HR employee dataset in R, answering 8 structured analytical questions covering workforce demographics, income distribution, statistical hypothesis testing and job satisfaction patterns. Both descriptive statistics and inferential statistical tests were applied throughout.

---

## Dataset

HR employee dataset — 1,470 employees  
Variables: age, monthly income, commuting distance, education level, sex, job satisfaction

---

## Analysis — 8 Questions

### Q1 — Age Profile of the Workforce
- Age range: 18–60 years | Mean: 36.9 | Median: 36 | IQR: 30–43
- Broadly balanced distribution with no extreme outliers
- **Visualisation: Box plot**

### Q2 — Average Monthly Income
- Income range: £504–£9,999 | Mean: £3,251 | Median: £2,460
- Positively skewed — most employees earn lower-to-mid range
- **Visualisation: Violin plot**

### Q3 — Commuting Distance
- Distance range: 1–29 units | Mean: 9.19 | Median: 7 | IQR: 2–14
- Right-skewed — long commutes are uncommon
- **Visualisation: Histogram**

### Q4 — Educational Background
- A-level or equivalent: 38.9% | HE degree: 27.1% | 5+ GCSEs: 19.2% | No qualifications: 11.6% | Postgraduate: 3.3%
- **Visualisation: Bar chart**

### Q5 — Income vs Age (Correlation)
- Pearson's r = 0.497, p < 2.2e−16 — moderate positive relationship
- Older employees tend to earn more
- **Visualisation: Scatterplot**

### Q6 — Income by Sex (Hypothesis Test)
- **H₀:** No significant difference in mean income between sexes
- Welch two-sample t-test: p = 0.2218 — H₀ not rejected
- No statistically significant income difference between male and female employees
- **Visualisation: Boxplot**

### Q7 — Income by Education (ANOVA + Post-hoc)
- One-way ANOVA: F(4, 1465) = 3.893, p = 0.00377 — significant effect of education on income
- **Tukey HSD post-hoc test** key findings:
  - HE degree vs no qualifications: p = 0.044
  - Postgraduate vs no qualifications: p = 0.005
  - Postgraduate vs 5+ GCSEs: p = 0.041
- Higher education significantly associated with higher income
- **Visualisation: Boxplot**

### Q8 — Job Satisfaction by Sex and Education (Chi-squared Tests)
- **By sex:** χ²(3) = 2.5477, p = 0.4667 — no significant association
- **By education:** χ²(12) = 13.03, p = 0.3669 — no significant association
- Job satisfaction is broadly consistent regardless of sex or educational background

---

## Statistical Tests Applied

- Descriptive statistics (mean, median, IQR, range)
- Pearson correlation
- Welch two-sample t-test
- One-way ANOVA
- Tukey HSD post-hoc test
- Pearson's Chi-squared test of independence

---

## Visualisations Produced

Box plot · Violin plot · Histogram · Bar chart · Scatterplot · Comparative boxplots

---

## Tools & Technologies

- R (statistical computing)
- ggplot2 (data visualisation)
- Base R statistical test functions

---

MSc Data Science, Kingston University, London
