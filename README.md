# 🚲 Yulu Bike Demand Analysis using Hypothesis Testing

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![SciPy](https://img.shields.io/badge/SciPy-Hypothesis%20Testing-8CAAE6?logo=scipy)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Statistical%20Modeling-red)

</p>

---

# 📄 Project Deliverables

| Resource | Description |
|----------|-------------|
| 📓 **Jupyter Notebook** | **[View Complete Analysis](https://github.com/Richa-Jain108/yulu-bike-demand-analysis-hypothesis-testing/blob/main/notebooks/yulu_bike_demand_analysis_hypothesis_testing%20.ipynb)** |
| 📑 **Project Report (PDF)** | **[View Business Report](https://github.com/Richa-Jain108/yulu-bike-demand-analysis-hypothesis-testing/blob/main/reports/yulu_bike_demand_analysis_report.pdf)** |
| 📊 **Dataset** | **[Download Dataset](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089)** |

---

# 📌 Business Problem

Yulu is India's leading micro-mobility platform providing shared electric bicycles for urban commuting. Despite its rapid expansion and innovative mobility solutions, the company experienced a decline in revenues and wanted to understand the factors influencing customer demand.

As a Data Analyst, the objective of this project is to identify the variables that significantly impact bike rental demand using Exploratory Data Analysis and Statistical Hypothesis Testing. The findings provide actionable business recommendations that can help improve operational planning, customer engagement, and revenue growth.

---

# 🎯 Business Questions Answered

This project answers several business-critical questions:

- Does bike demand differ between working days and non-working days?
- Does weather significantly influence bike rental demand?
- Does bike demand vary across different seasons?
- Is weather dependent on season?
- Which business variables have the strongest influence on customer demand?
- What actionable recommendations can Yulu implement to increase bike rentals?

---

# 📊 Dataset Overview

| Attribute | Details |
|-----------|---------|
| Dataset | Bike Sharing Demand Dataset |
| Records | 10,886 |
| Features | 12 |
| Domain | Micro-Mobility / Transportation |
| Target Variable | `count` (Total Bike Rentals) |

### Features

- Datetime
- Season
- Holiday
- Working Day
- Weather
- Temperature
- Feels Like Temperature
- Humidity
- Wind Speed
- Casual Users
- Registered Users
- Total Rentals

---

# 🛠️ Tech Stack

| Category | Tools |
|----------|------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Statistical Analysis | SciPy, Statsmodels |
| Environment | Jupyter Notebook |

---

# 🔍 Project Workflow

### 1️⃣ Data Understanding

- Dataset inspection
- Data types
- Missing value analysis
- Duplicate analysis
- Statistical summary

---

### 2️⃣ Exploratory Data Analysis

Performed extensive visual exploration including:

- Distribution Analysis
- Countplots
- Histograms
- Boxplots
- Correlation Analysis
- Relationship between variables
- Outlier Detection

---

### 3️⃣ Hypothesis Testing

Several statistical tests were conducted.

### ✅ Independent Two Sample t-Test

Business Question:

> Does bike demand differ significantly between working days and non-working days?

---

### ✅ One-Way ANOVA

Business Questions:

- Does weather significantly affect bike rentals?
- Does season significantly affect bike rentals?

---

### ✅ Chi-Square Test

Business Question:

> Is weather condition dependent on season?

---

### 4️⃣ Statistical Assumption Validation

Before hypothesis testing, assumptions were verified using:

- Histogram
- Q-Q Plot
- Shapiro-Wilk Test
- Levene's Test

---

# 📈 Key Insights

Some of the major business insights include:

- Working days significantly influence bike rental demand.
- Weather conditions have a measurable impact on customer demand.
- Bike rentals vary significantly across different seasons.
- Weather and season are statistically associated.
- Temperature and humidity show meaningful relationships with rental counts.
- Registered users contribute substantially more rentals than casual users.

---

# 💡 Business Recommendations

Based on statistical evidence, Yulu can improve business performance by:

- Increase bicycle availability during high-demand seasons.
- Optimize fleet allocation based on weather forecasts.
- Launch promotional campaigns during low-demand periods.
- Introduce dynamic pricing strategies.
- Improve customer retention for casual riders.
- Use weather-aware operational planning to maximize utilization.

---
## 🎯 Business Impact

This analysis enables Yulu to:

- Optimize fleet allocation
- Improve operational planning
- Increase bike utilization
- Design weather-aware marketing campaigns
- Improve seasonal demand forecasting
---

# 📚 Statistical Techniques Used

- Exploratory Data Analysis (EDA)
- Outlier Analysis
- Correlation Analysis
- Independent Two Sample t-Test
- One-Way ANOVA
- Chi-Square Test
- Normality Testing
- Equality of Variance Testing

---

# 📂 Repository Structure

```
yulu-bike-demand-analysis-hypothesis-testing
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data
│   └── bike_sharing.txt
│
├── notebooks
│   └── yulu_bike_demand_analysis_hypothesis_testing.ipynb
│
└── reports
    └── yulu_bike_demand_analysis_report.pdf
```

---

# 🚀 Deliverables

✅ End-to-End Data Analytics Project

✅ Exploratory Data Analysis

✅ Business Insights

✅ Statistical Inference

✅ Hypothesis Testing

✅ ANOVA

✅ Chi-Square Test

✅ Business Recommendations

---

# ⭐ Key Skills Demonstrated

- Business Problem Solving
- Exploratory Data Analysis
- Statistical Inference
- Hypothesis Testing
- Data Visualization
- Business Communication
- Python Programming
- Analytical Thinking
- Insight Generation
- Data Storytelling

---

# 👩‍💻 Author

**Richa Jain**

Aspiring Data Analyst | Python | SQL | Statistics | Tableau 

If you found this project useful, consider ⭐ starring the repository.
