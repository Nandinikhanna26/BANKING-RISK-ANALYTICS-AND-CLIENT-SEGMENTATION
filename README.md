# Risk Analysis in Banking Domain

This project presents a business-focused risk analysis of banking customers, leveraging Python for data modeling and Power BI for executive dashboards. The goal is to enable financial institutions to identify high-risk clients, optimize loan-deposit strategies, and align customer segmentation with business objectives.

---

## Objective

To support risk management teams in identifying customer risk profiles and behavioral trends, thereby reducing potential financial exposure and enhancing targeting strategies for loans and deposit products.

---

## 1. Python Notebook: [risk_analysis.ipynb](https://github.com/Nandinikhanna26/BANKING-RISK-ANALYTICS-AND-CLIENT-SEGMENTATION/blob/main/risk%20analysis.ipynb)

### Business Purpose:
To conduct in-depth exploratory analysis and calculate custom risk metrics that inform the bank’s credit strategy.

### Actions Taken:
- Imported and cleaned transactional and customer data using Pandas
- Engineered a **Risk Ratio** metric combining **loan amount**, **credit card balance**, and **deposit volume**
- Segmented customers by **income**, **loyalty**, **occupation**, and **age**
- Generated visualizations to discover patterns in credit exposure and deposit strength

### Business Insights:
- Clients with **low loyalty and moderate deposits** exhibited the **highest risk**, supporting prioritization for credit monitoring
- **Mid-income customers (₹30k–₹70k/month)** emerged as the most financially active, holding **54% of loans** and **56% of deposits**
- Top 5 high-risk clients had **risk ratios above 23**, signaling potential red flags for review

---

## Dashboard 1: Loan Analysis

### Purpose:
To assess loan portfolio composition across client segments and banking divisions.

### Key Insights:
- **Private Banking clients** accounted for **45% of total loan volume (~₹1.93B)**, highlighting its strategic importance
- **Business lending** dominates at ₹2.53B vs. ₹1.75B in bank loans — showing heavier institutional focus
- **Mid-income customers** held **53.95% of loan value**, confirming them as a key target segment for credit products
- **Top professions with high loan amounts** included Account Coordinators, Structural Analysts, and Database Admins

---

## Dashboard 2: Deposit Analysis

### Purpose:
To evaluate savings and checking behavior, and identify customer groups contributing most to liquidity.

### Key Insights:
- Total deposits stood at **₹3.78B**, with **₹2.05B** from direct bank deposits, and remaining from checking/saving accounts
- **Commercial Banking** drives **44.88% of total deposits**, underscoring its role in maintaining liquidity
- **Mid-income clients** are again the largest contributors (55.71%) to deposits — ideal for bundled product marketing
- Professions like Structural Analyst, Social Worker, and Office Admin III led deposit volume, aiding targeting efforts

---

## Dashboard 3: Risk Analysis Summary

### Purpose:
To unify loan, deposit, and demographic risk signals into a single executive view.

### Key Insights:
- Top 5 high-risk clients were flagged using a composite risk ratio metric — one with a loan of ₹13.6M had only ₹267K in deposits
- **Clients with Silver loyalty tier and early year-of-joining had consistently high risk ratios**
- Risk distribution by nationality showed **Asian clients had the highest risk weighting and deposit volume correlation**
- Majority of clients had **risk weighting of 2**, but **27% were in level 3 or above**, suggesting significant monitoring opportunity

---

## Business Value Delivered

- Enabled precise identification of **top high-risk clients** for proactive risk control
- Helped segment customer base for **targeted loan product development**
- Informed **branch and channel strategy** by comparing division-level asset/deposit patterns
- Supported **income-based product alignment** to improve ROI across customer brackets

---

## Tools & Technologies

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Power BI (for dashboard development)
- Jupyter Notebook (for analysis and modeling)



---

## Author

[Nandini Khanna]  
Minor in Data Science | Finance & Risk Analytics Focus  
[[LinkedIn URL](https://www.linkedin.com/in/nandini-khanna-18a622325/)]

