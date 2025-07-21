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

## 2. Power BI Dashboards

### Dashboard 1: Client Risk Profiling

**Purpose:**  
To visualize and identify the most financially risky clients and demographic segments contributing to elevated credit exposure.

**Key Business Insight:**  
- Majority of high-risk clients fell under **loyalty level 0** and **age group 25–35**
- Professions such as **Engineer** and **Doctor** appeared frequently among high-risk profiles, suggesting sectors with higher credit leverage
- Allows risk teams to focus surveillance efforts on targeted segments

---

### Dashboard 2: Loan and Deposit Distribution by Income

**Purpose:**  
To guide product strategy and pricing by understanding income group behavior across credit and savings products.

**Key Business Insight:**  
- **Mid-income bracket** contributed most significantly to both loans and deposits
- **High-income clients** had **lower loan participation**, highlighting potential for high-end lending products
- Confirms where to focus cross-selling of credit and investment offerings

---

### Dashboard 3: Banking Division Performance

**Purpose:**  
To analyze performance across Retail, Private, and Commercial banking channels in terms of asset and liability generation.

**Key Business Insight:**  
- **Private Banking** accounted for the **highest share of loan value (~₹1.93B, 45%)**
- **Commercial Banking** held **~45% of deposits (~₹1.69B)**, indicating a strong source of low-cost funds
- Retail division performed steadily across both but with smaller volumes—suggesting room for targeted growth

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

