# Customer Churn Analysis & Prediction

## 📌 Project Overview
This project focuses on analyzing telecom customer churn behavior and identifying factors that contribute to customer attrition. The objective is to generate actionable business insights and support proactive retention strategies using data analytics and visualization.

## 📊 Dashboard Preview
![Customer Churn Dashboard](https://raw.githubusercontent.com/ThotakuraJayanth/Customer-Churn-Analysis/main/Dashboard.jpg)

---

## ⚠️ Business Problem
Customer churn is a major challenge for telecom companies, as losing customers directly impacts recurring revenue and long-term profitability. This project aims to identify high-risk customer segments, understand churn drivers, and recommend data-driven retention strategies.

## 📂 Dataset Information
* **Dataset:** [Telco Customer Churn Dataset](Customer_Churn_Analysis.csv)
* **Total Records:** 7,032 customers
* **Features:** Demographics, Contract type, Monthly charges, Payment method, Internet service, Tenure, and Churn status.

## 🛠️ Tools & Technologies
* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Power BI** (Interactive Dashboarding)
* **Jupyter Notebook** (Data Cleaning & EDA)

## 🔄 Project Workflow
1.  **Data Cleaning:** Handled missing values (specifically in Total Charges) and converted data types.
2.  **EDA:** Exploratory Data Analysis to find correlations between service types and churn.
3.  **Visualization:** Built an interactive dashboard in Power BI.
4.  **Insights:** Extracted key behavioral patterns of churning customers.

## 💡 Key Findings
* **Churn Rate:** 26.58% (1,870 out of 7,032 customers).
* **Contract Risk:** Month-to-month contract customers show the highest risk.
* **Tech Influence:** Fiber optic users have significantly higher churn than DSL users.
* **Payment Method:** Electronic check users are more likely to leave compared to credit card or bank transfer users.

## 🚀 Business Recommendations
* **Contract Incentives:** Offer discounts to transition month-to-month users to 1 or 2-year contracts.
* **Service Check-ups:** Investigate fiber optic performance/pricing to address high churn in that segment.
* **Auto-Pay Promotion:** Encourage automated payment methods to reduce friction in billing.
* **Loyalty Programs:** Target high-tenure customers with personalized offers before they reach "churn-risk" milestones.

## 📁 Project Structure
```bash
Customer-Churn-Analysis/
│
├── Customer_Churn_Analysis.csv   # Raw Dataset
├── Customer_Churn_Analysis.ipynb # Python Analysis & Cleaning
├── Customer_Churn_Analysis.pbix  # Power BI File
├── Dashboard.jpg                 # Dashboard Screenshot
└── README.md                     # Project Documentation
