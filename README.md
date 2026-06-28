# 📊 Telco Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg?style=flat&logo=Jupyter)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%20%7C%20NumPy%20%7C%20Seaborn%20%7C%20Matplotlib-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

> An Exploratory Data Analysis (EDA) project investigating the underlying friction points driving customer attrition in the telecommunications sector, paired with actionable business retention strategies.

---

## 📌 Executive Overview

In the telecommunications industry, acquiring a new customer is significantly more expensive than retaining an existing one. This project analyzes a dataset of **7,043 Telco customers** to diagnose why the business is experiencing a **26.54% overall churn rate**. 

Through exploratory data visualization and statistical grouping, this analysis answers four core business questions:
1. *When are customers most vulnerable to leaving?*
2. *Which specific service tiers are driving customer dissatisfaction?*
3. *Do demographic factors dictate churn?*
4. *How can the business mathematically alter its onboarding to protect Monthly Recurring Revenue (MRR)?*

💡 Key Analytical Findings
The 6-Month Cliff: Customer attrition is heavily front-loaded. The vast majority of customer churn occurs within Months 1 to 6 of onboarding. If a customer survives past Month 24, their probability of churning drops to near-zero.

The "Month-to-Month" Trap: Contract type is the single strongest indicator of churn. Month-to-month contracts account for over 80% of all lost customers, whereas 1-Year and 2-Year contracts exhibit exceptionally high stability.

The Fiber Optic Paradox: Premium Fiber Optic internet subscribers churn at a much higher rate than standard DSL subscribers, pointing to a massive disconnect between high monthly pricing and delivered technical stability.

Senior Citizen Vulnerability: While Senior Citizens make up a small fraction of the user base (~16%), they churn at an alarming 41.7% (compared to 23.6% for younger demographics). Gender was proven to have 0% statistical impact on churn.

Payment Friction: Customers paying manually via Electronic Check churn far more frequently than those set up on automated Credit Card or Bank Transfer autopay.

🎯 Strategic Business Recommendations
Based on the data, the business should pivot its retention budget toward four specific operational initiatives:

The Autopay Migration Push: Offer a $5.00/month statement credit to any customer willing to migrate from Electronic Check to an automated payment method.

Tenure Milestone Intervention: Target Month-to-Month users at their 3rd and 6th months with heavily discounted upgrade offers to lock them into 1-Year contracts before they hit the historical attrition peak.

Fiber Optic Infrastructure Audit: Institute an automated, mandatory check-in from Technical Support 14 days after every new Fiber Optic installation to catch local network friction before it becomes cancellation churn.

"Senior Peace of Mind" Tiers: Create a dedicated Senior Citizen onboarding bundle that automatically bakes Tech Support and Online Security into the base price.

🛠️ Tech Stack & Tools
Environment: Jupyter Notebook

Language: Python 3.x

Data Manipulation: pandas, numpy

Data Visualization: matplotlib.pyplot, seaborn (countplots, KDE histograms, stacked bar distributions)

---

## 📂 Repository Structure

```text
├── TCA.ipynb                 # Core Jupyter Notebook containing all cleaning, EDA, and charts
├── Telco-Customer-Churn.csv  # Raw Dataset 
├── Executive_Summary.pdf     # 4-Page PDF presentation of findings & recommendations
└── README.md                 # Project Documentation
