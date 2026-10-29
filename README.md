# 📊 Telco Customer Churn Analysis

### Exploratory Data Analysis Using Python

## 📌 Project Overview

This project explores customer churn in a telecommunications company using Python. The goal is to identify customer segments with higher churn rates, understand patterns associated with customer retention, and provide actionable business recommendations.

The analysis focuses on contract types, customer tenure, and demographic characteristics.

## 🎯 Business Objectives

- Analyze the overall customer churn rate.
- Examine how contract types and customer tenure relate to churn.
- Identify customer segments with higher churn rates.
- Provide data-driven recommendations to support customer retention strategies.

## 🛠️ Tools & Technologies

- **Python** — Data analysis
- **Pandas** — Data cleaning, manipulation, and exploratory analysis
- **Matplotlib** — Data visualization
- **Jupyter Notebook** — Analysis and documentation

## 📂 Dataset

**Source:** IBM Telco Customer Churn Dataset

The original dataset contains 7,043 customer records and 21 columns.

After cleaning, 7,032 records were retained for analysis.

### Data Cleaning

- Converted `TotalCharges` from text to numeric values.
- Identified and removed 11 records with missing `TotalCharges`.
- Checked for duplicate records and customer IDs.
- Verified categorical values for consistency.

## 📈 Key Findings

| Metric | Churn Rate |
|---|---:|
| Overall Customer Churn | 26.6% |
| Month-to-Month Contracts | 42.7% |
| One-Year Contracts | 11.3% |
| Two-Year Contracts | 2.8% |
| Customers in Their First Year | 47.7% |
| First-Year Month-to-Month Customers | ~51% |

### 🔍 Key Insights

**1. Contract Type Matters**

Customers with month-to-month contracts have significantly higher churn rates than customers with longer-term contracts.

**2. Early Customer Retention Is Critical**

Customers in their first 12 months have the highest churn rate, suggesting that early engagement deserves particular attention.

**3. Combining Contract Type and Tenure Reveals Higher-Risk Segments**

First-year customers on month-to-month contracts have the highest observed churn rate, approximately 51%.

**4. Customer Characteristics Show Different Churn Patterns**

Higher churn rates were observed among senior citizens, customers without partners, and customers without dependents.

These findings describe historical patterns and do not establish causation or predict individual customer behavior.

## 💡 Business Recommendations

- Test targeted retention incentives for first-year month-to-month customers.
- Improve customer onboarding and engagement during the first 12 months.
- Explore incentives for longer-term contracts.
- Monitor churn patterns across customer segments to support retention decisions.

## 🚀 How to Run

1. Download or clone this repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas matplotlib jupyter
   ```

3. Open `churn_analysis.ipynb` in Jupyter Notebook.
4. Ensure `WA_Fn-UseC_-Telco-Customer-Churn.csv` is in the same directory.
5. Run all notebook cells to reproduce the analysis.

## 📓 Project Notebook

Explore the complete analysis, Python code, and visualizations:

**[View Customer Churn Analysis Notebook](churn_analysis.ipynb)**

## ✅ Conclusion

This analysis identified contract type and customer tenure as important factors associated with customer churn.

The findings highlight the importance of focusing retention efforts on newer customers, particularly those with month-to-month contracts.

The project demonstrates the use of Python for data cleaning, exploratory data analysis, visualization, and translating analytical findings into business recommendations.
