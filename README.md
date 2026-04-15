# Loan Approval Analysis (Business Intelligence & Data Mining)

## 📊 Overview
This project explores loan approval decisions using Business Intelligence techniques and data mining. The dataset, sourced from Kaggle, contains applicant information such as income, credit score, employment status, and asset values.

The goal of this project is to:
- Identify patterns influencing loan approval
- Support data-driven decision making in banking
- Build predictive models to classify loan outcomes

---

## 🛠️ Tools & Technologies
- Tableau (Data Visualization)
- Weka (Data Mining - J48 Decision Tree)
- Data Warehousing Concepts
- Python/Excel (Data Preparation)

---

## 📈 Data Analysis & Visualization

A total of **10 interactive visualizations** were created in Tableau to explore key factors affecting loan approval:

### Key Insights:
- ✅ Approved applicants generally have **higher income and credit scores**
- ✅ Lower loan amounts are more likely to be approved
- ✅ Applicants with fewer dependents have higher approval rates
- ✅ Salaried individuals are more likely to be approved than self-employed
- ✅ Higher asset values (commercial/residential) increase approval chances

These insights highlight that **financial stability is the strongest driver of loan approval decisions**.

---

## 🤖 Data Mining (Decision Tree Model)

A **J48 Decision Tree algorithm** was implemented using Weka to classify loan approval outcomes.

### Model Iterations:
- **Iteration 1:** Full dataset → Accuracy: 97.74%
- **Iteration 2:** Removed weak predictors → Accuracy: 97.58%
- **Iteration 3 (Final Model):** Optimized features → Accuracy: **97.89%**

### Key Predictors:
- Credit Score (most important)
- Income
- Loan Amount
- Asset Values

### Key Rules Identified:
- Applicants with **credit score > 549** are highly likely to be approved
- High loan amount + low income → higher rejection probability
- Asset values improve approval chances in borderline cases

---

## 🧠 Business Impact

This analysis provides actionable insights for financial institutions:
- Improve risk assessment models
- Enhance loan approval accuracy
- Develop fair and data-driven lending policies
- Identify high-risk applicants early

---

## ⚖️ Data Ethics

This project considers ethical implications including:
- Fairness in decision-making (avoiding bias)
- Transparency of predictive models
- Compliance with data protection regulations (GDPR)

---

## 📁 Project Files
- Tableau Dashboard (.twbx)
- Dataset (sample/cleaned)
- Analysis Report
- Visualization Screenshots

---

## 📌 Note
This project was developed as part of academic coursework in Business Intelligence.

---

## 👤 Author
Aye Chan Moe  
BSc Computer Science – Middlesex University
