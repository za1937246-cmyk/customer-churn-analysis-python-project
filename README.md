# 🧾 Customer Churn Analysis

## 📊 Project Overview  
This project analyzes **customer churn** — identifying the key factors that influence customers to discontinue services.  
The analysis investigates how **contract types**, **payment methods**, **tenure**, and **demographics** impact churn rates.  
Using **Python** and data visualization, this project provides insights and recommendations to improve customer retention.

---

## 🎯 Objective  
To explore and analyze customer churn patterns by examining multiple factors such as:
- Payment methods  
- Contract types  
- Customer tenure  
- Internet service types  
- Demographic attributes  

The goal is to identify which factors are most strongly associated with churn and to guide data-driven retention strategies.

---

## 🖥️ Program & Libraries Used  

This project was created using **Python (Jupyter Notebook)**.  
The following libraries were used for analysis and visualization:

```python
# Importing necessary libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

## Library Roles:

pandas → Data cleaning, manipulation, and analysis

numpy → Numerical computations and data operations

matplotlib → Data visualization through bar charts and line graphs

seaborn → Enhanced statistical visualization with beautiful styling

## 🔍 Key Insights & Findings
### 📅 Contract Type and Churn

- **Month-to-month contracts:** 42% churn rate

- **One-year contracts:** 11% churn rate

- **Two-year contracts:** 3% churn rate
**💡 Insight:** Longer-term contracts significantly reduce churn. Customers with extended commitments are more loyal and less likely to leave.

### 💳 Payment Methods and Churn

- **Electronic check users:** 45% churn rate

- **Other methods (credit card, bank transfer, mailed check):** 15–18% churn rate
**💡 Insight:** Customers paying via electronic checks tend to churn more, possibly due to trust or convenience issues. Encouraging alternative payment methods may help retain customers.

🕐 Churn by Tenure

- **Less than 1 year:** 50% churn rate

- **1–3 years:** 35% churn rate

- **More than 3 years:** 15% churn rate
**💡 Insight:** Early customer engagement is crucial. The first year of a customer’s journey determines long-term retention.

### 🌐 Churn by Internet Service Type

- **Fiber Optic users:** 30% churn rate

- **DSL users:** 20% churn rate
**💡 Insight:** Higher churn among fiber optic users may indicate dissatisfaction with service quality or pricing. Continuous service improvement can mitigate this.

### 👴 Senior Citizens and Churn

- **Senior citizens (65+):** 41% churn rate

- **Non-senior citizens:** 26% churn rate
**💡 Insight:** Senior customers may require personalized support and communication to stay engaged.

## 📈 Visualizations & Data Insights

The following visualizations were created using Matplotlib and Seaborn:

- **Bar Charts** — Show churn rate comparison across payment methods and contract types.

- **Line Graphs** — Display declining churn trend as tenure increases.

- **Distribution Plots** — Visualize churn percentages across demographics and internet service types.

**Percentage Distribution Summary:**

| Factor | Category | Churn Rate |
|:--|:--|:--:|
| Payment Method | Electronic Check | 45% |
| Payment Method | Credit Card | 15% |
| Contract Type | Month-to-Month | 42% |
| Contract Type | One-Year | 11% |
| Contract Type | Two-Year | 3% |
| Tenure | < 1 Year | 50% |
| Tenure | > 3 Years | 15% |

---
## 🧠 Recommendations
1. **Promote Long-Term Contracts**

Offer incentives such as discounts or loyalty rewards for customers who commit to yearly or bi-annual plans.

2. **Address Payment Method Concerns**

Launch campaigns to educate and assist customers in switching from electronic checks to secure payment methods like credit cards or bank transfers.

3. **Enhance Early-Stage Engagement**

Develop onboarding programs, welcome offers, and personalized support during the first year to build trust and satisfaction.

4. **Target Senior Customers**

Create senior-friendly support services, simplified billing options, and exclusive retention offers for the 65+ demographic.

5. **Monitor Service Quality**

For Fiber Optic users, conduct feedback surveys and optimize service reliability to lower churn rates.

## 🧮 Steps Performed

- **Data Loading:** Imported the dataset using pandas.

- **Data Cleaning:** Removed missing values, duplicates, and formatted data types.

- **Exploratory Data Analysis (EDA):*8 Used descriptive statistics to understand customer behavior.

- **Visualization:** Created graphs to show churn patterns across categories.

**Insights & Recommendations:** Derived key findings and actionable strategies.

## 📚 Conclusion

This analysis demonstrates that:

Long-term contracts and secure payment methods play a vital role in retention.

Early engagement within the first year is critical to reduce churn.

Special attention is needed for senior customers and Fiber Optic users.

By implementing these recommendations, the company can reduce churn rates and increase customer lifetime value.

## 📁 Project Files

customer_churn_analysis.ipynb — Jupyter Notebook with Python code and visualizations

data.csv — Dataset used for analysis (if available)

README.md — Project documentation (this file)

## ⚙️ How to Run This Project

Clone or download this repository.

Make sure Python is installed (preferably version 3.8+).

Install required libraries using the following command:

pip install pandas numpy matplotlib seaborn


Open the notebook file:

jupyter notebook customer_churn_analysis.ipynb


Run all cells to reproduce the analysis and visualizations.

## 💡 Future Improvements

Add predictive modeling using logistic regression or decision trees.

Include customer segmentation with clustering techniques.

Deploy an interactive dashboard using Streamlit or Plotly Dash.

## ✨ Author

Zainab Batool
Data Analyst | Python



