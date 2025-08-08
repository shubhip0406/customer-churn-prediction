# Customer Churn Prediction

**Author:** Shubhi Phartiyal  

Predicting which customers are likely to close their accounts helps banks take proactive retention measures.  
This project uses **machine learning** to identify customers at risk of churn, understand key drivers, and recommend targeted actions.

---

## Overview
In the competitive banking sector, retaining existing customers is a top priority.  
Using data from a European bank with **10,000 customer records**, this project applies classification models to predict churn and provide actionable business insights.

**Business Questions:**
1. Can we predict which customers are likely to churn?  
2. What characteristics are most associated with churn?  
3. How can this information help reduce churn?

---

## Dataset
- **Source:** European bank customer data
- **Records:** 10,000 customers
- **Features:**
  - Credit score
  - Age
  - Balance
  - Geography
  - Gender
  - Number of products
  - Activity level
  - Churn label (`Exited`)

---

## Methodology
**Process followed:**  
`Problem Definition → EDA → Modeling → Evaluation → Recommendations`

**Models tested:**
- Logistic Regression (baseline)
- Random Forest *(best performance)*
- Support Vector Machine (SVM)

**Best Model: Random Forest**
- Accuracy: **86%**
- ROC AUC: **0.87**
- Precision: **79%**
- Recall: **82%**

---

## Key Insights
- **Age ↑** → Higher churn
- **Inactivity ↑** → Higher churn
- **High balance + inactivity** → Higher churn
- **Geography: Germany** → More churn

---

## Recommendations
- Target **high-risk customers** with personalized campaigns (loyalty points, discounts)
- Re-engage inactive customers via automated email/SMS
- Create **geo-specific retention strategies** for Germany
- Integrate churn scores into CRM for **priority outreach**
- Monitor key churn drivers with internal dashboards

---

## Business Impact
**Projected Gains:**
- Reduce churn by **10–15%** through targeted retention
- Improve Customer Lifetime Value (CLV)
- Increase marketing ROI with smarter targeting

**Risks Prevented:**
- Lost revenue from **220 false negatives**
- Wasted resources on **54 false positives**

---

## 📂 Repository Structure
