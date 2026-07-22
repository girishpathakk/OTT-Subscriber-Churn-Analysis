# 📺 OTT-Subscriber-Churn-Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green)
![SQLite](https://img.shields.io/badge/SQLite-3.x-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

##  About the Project
In the hyper-competitive OTT (Over-The-Top) streaming industry (similar to Netflix, Hotstar, Prime), customer retention is the ultimate metric for sustainable growth. This project focuses on identifying high-risk subscribers by analyzing a multi-dimensional dataset. 

By integrating raw database tables (Customer Demographics, Subscription Details, and Support Escalations), this project uncovers behavioral patterns that lead to churn. The analytical framework used here is highly scalable and applicable to other subscription-based industries like **E-commerce, SaaS, Fintech, and Adtech**.

## Library Requirements

- Pandas
- NumPy
- SQLite
- Matplotlib
- Seaborn

---

## 🎯 Business Problem

In the hyper-competitive OTT industry (Netflix, Hotstar, 
Amazon Prime), subscriber retention is the #1 priority. 
This project analyzes a multi-dimensional subscriber dataset 
to identify high-risk churn segments and deliver actionable 
retention recommendations.

**Key Business Questions Answered:**
- Which customer segments have the highest churn rate?
- Does subscription plan affect churn probability?
- Do support complaints correlate with churn?
- What is the revenue impact of churn?
- Why are customers cancelling their subscriptions?

---

## 📊 Key Findings

| Metric | Value |
|--------|-------|
| Overall Churn Rate | 28.6% |
| Monthly Revenue Lost | ₹73.94 |
| Avg Customer Tenure | 56.3 months |
| Highest Risk Segment | Basic Plan + Monthly Contract |

### 🔴 Top Risk Segments
- **Basic Plan** customers → Highest churn rate
- **Monthly contract** customers → Very high churn
- **Age 41-50** group → High risk group
- **Customers who complained** → Alarming churn rate

### 📉 Why Customers Left
1. Switched to Competitor (most common)
2. Too Expensive
3. Not Enough Content
4. Poor Streaming Quality
5. Forgot to Cancel Trial

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core programming |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| SQLite3 | Database management |
| Matplotlib | Visualizations |
| Seaborn | Statistical charts |
| Jupyter Notebook | Development environment |

---

## 📁 Project Structure

```text
ott-subscriber-churn-analysis/
├── 01_Data/
│   ├── customer_churn_data_raw.xlsx
│   ├── master_churn_data.csv 
│   └── problem_statement.docx
├── 02_Database/
│   ├── customer_churn.db
│   └── customer_churn_clean.db
├── 03_Notebooks/
│   ├── phase1_data_pipeline_ETL.ipynb
│   └── phase2_eda_visualization.ipynb
├── 04_Output/
│   └── [all charts .png]
└── README.md
```


---

## 🔄 Project Pipeline

```text
Excel Raw Data
↓
Python Pipeline (Phase 1)
↓
SQLite Database
↓
EDA & Visualization (Phase 2)
↓
Business Insights & Recommendations
```

---

## 📈 Key Visualizations

### Overall Churn Rate
![Churn](https://github.com/girishpathakk/OTT-Subscriber-Churn-Analysis/blob/main/04_Output/chart1_overall_churn.png)

### Plan Type Analysis
![Plan](https://github.com/girishpathakk/OTT-Subscriber-Churn-Analysis/blob/main/04_Output/chart2_plan_churn.png)

### Cancellation Reason
![Reason](https://github.com/girishpathakk/OTT-Subscriber-Churn-Analysis/blob/main/04_Output/chart6_cancellation_reasons.png)

### Executive Dashboard
![Dashboard](https://github.com/girishpathakk/OTT-Subscriber-Churn-Analysis/blob/main/04_Output/dashboard_executive_summary.png)

---

## 💡 Business Recommendations

1. **Convert Monthly → Annual**
   Offer 2 months free on annual upgrade

2. **Basic Plan Retention**
   Trial premium upgrade for basic subscribers

3. **Post-Complaint Follow-up**
   Contact within 24hrs of any complaint

4. **Age 41-50 Targeting**
   Family plan + premium content offers

5. **Price-Sensitive Customers**
   Loyalty discount program



---

## 👤 Author

**Girish Pathak**
- LinkedIn: https://linkedin.com/in/girishpathakk
- GitHub: https://github.com/girishpathakk
- Email: girish.pathak.ds@gmail.com

---

*This project is applicable to OTT, SaaS, Fintech, 
Telecom, and E-commerce industries.*
