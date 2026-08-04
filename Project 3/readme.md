# IT Budget Variance Analysis

## 📌 Project Overview

This project analyzes IT expenditure data to identify the key drivers of budget variance by comparing **Actual Spend** with **Planned Spend**. The objective is to uncover areas responsible for overspending, understand spending patterns across different business dimensions, and perform root cause analysis to provide actionable business recommendations.

---

## 🎯 Problem Statement

The organization wants to understand why Actual IT expenditure deviated from the planned budget.

This project answers questions such as:

- What is the overall budget variance?
- Which Business Area contributes the most to the variance?
- Which Country, IT Area, and IT Sub Area are driving the overspend?
- What is the root cause behind the variance?
- How did the variance change over time?

---

## 📂 Dataset Information

The dataset contains IT expenditure records with the following dimensions:

- Date
- Business Area
- Region
- Country
- IT Area
- IT Sub Area
- Cost Element Group
- Cost Element Sub Group
- Cost Element Name
- Actual Spend
- Forecast Spend
- Planned Spend

---

## 🛠️ Data Cleaning

The following preprocessing steps were performed:

- Renamed column names
- Converted column names to lowercase
- Replaced spaces with underscores
- Converted Date column to datetime format
- Removed duplicate records
- Handled missing values
- Created a separate analysis dataframe (`analysis_df`)
- Created variance metrics

---

## 📊 KPIs Created

- Total Actual Spend
- Total Forecast Spend
- Total Planned Spend
- Actual vs Forecast Variance
- Actual vs Plan Variance

---

## 📈 Analysis Performed

### 1. Monthly Trend Analysis

- Monthly Actual Spend
- Monthly Planned Spend
- Monthly Variance Trend

---

### 2. One-Dimensional Analysis

Performed analysis on:

- Business Area
- Country
- IT Area

---

### 3. Two-Dimensional Analysis

Performed analysis on:

- Business Area × Country
- Business Area × IT Area
- Country × IT Area
- IT Area × IT Sub Area

---

### 4. Root Cause Analysis

A hierarchical drill-down approach was used to identify the primary driver of budget variance.

Analysis Path:

Overall Variance
→ Infrastructure Business Area
→ Infrastructure IT Area
→ Data Center IT Sub Area
→ Hardware & Software Cost Element Group

---

## 📌 Key Insights

### Insight 1

Infrastructure Business Area recorded the highest negative Actual vs Plan variance and is the largest contributor to the overall budget overspend.

### Insight 2

Within the Infrastructure Business Area, the Infrastructure IT Area contributed the highest variance.

### Insight 3

Within the Infrastructure IT Area, the Data Center IT Sub Area generated the highest negative variance.

### Insight 4

Within the Data Center IT Sub Area, the Hardware & Software Cost Element Group was identified as the primary root cause of the overspend.

### Insight 5

Monthly trend analysis showed that January recorded the highest variance, while August recorded the lowest variance, indicating a gradual improvement in budget adherence over time.

---

## 💡 Business Recommendations

- Review Infrastructure Business Area spending regularly.
- Audit Infrastructure IT Area expenditures.
- Optimize Data Center operational costs.
- Review Hardware & Software procurement strategy.
- Evaluate vendor contracts and software licensing costs.
- Continue the budget control practices that improved spending performance in later months.

---

## 📊 Visualizations

The project includes:

- KPI Summary
- Business Area Variance
- Actual vs Planned Spend Comparison
- Monthly Variance Trend
- Root Cause Analysis

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📌 Conclusion

This project demonstrates an end-to-end data analytics workflow including data cleaning, exploratory data analysis, KPI development, root cause analysis, business storytelling, and actionable recommendations.

The analysis identified the Infrastructure Business Area as the primary contributor to budget variance. A structured drill-down approach further revealed that the Hardware & Software Cost Element Group within the Data Center IT Sub Area was the key driver of overspending.

---

## 👨‍💻 Author

**Altaf Mansuri**

Aspiring Data Analyst | Python | SQL | Power BI | Pandas
