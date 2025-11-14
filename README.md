# Banking_Data_EDA_Python
This project performs an end-to-end exploratory data analysis on a banking dataset of customers with financial, demographic, transaction, loan and credit-related variables. The analysis uncovers customer behavior, financial patterns, loan portfolio characteristics, transaction trends, anomaly detection insights, and correlation structure.



# 🏦 Banking Data Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-orange?logo=matplotlib)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Graphics-00b4d8)
![Jupyter](https://img.shields.io/badge/Notebook-Interactive-yellow?logo=jupyter)

## 📌 Project Overview
This project performs a **comprehensive Exploratory Data Analysis (EDA)** on a structured banking dataset containing **5,000 customer records** with **40 features**, covering:

- Customer demographics  
- Financial metrics  
- Loan portfolio details  
- Transaction history  
- Credit card behavior  
- Feedback & resolution  
- Anomaly detection  
- Correlation structure  

The goal is to uncover patterns, trends, and data quality insights that support deeper business understanding and ML-readiness.

---

## 📂 Dataset Summary
- **Size:** 5,000 rows × 40 columns  
- **Features include:**
  - 👤 *Customer Info:* Age, Gender, Address, City  
  - 💳 *Account Metrics:* Account Type, Balance, Credit Limit, Card Type  
  - 💵 *Transactions:* Amount, Type, Balance After Transaction  
  - 🏦 *Loans:* Loan Amount, Type, Status, Interest Rate  
  - ⭐ *Customer Experience:* Feedback Type, Resolution Status  
  - ⚠️ *Anomaly Flag:* Normal (1) vs Anomaly (-1)  

---

## 🧰 Tech Stack
| Component | Used For |
|----------|----------|
| **Python** | Core Programming |
| **Pandas** | Data Cleaning & Processing |
| **NumPy** | Numerical Computations |
| **Matplotlib / Seaborn** | Visual Analytics |
| **Jupyter Notebook** | Interactive EDA |

---

## 📊 Key Analyses Performed

### 🔍 1. Initial Data Exploration
- Displayed shape, column info, and first few rows  
- Verified datatypes & non-null counts  
- No missing values or duplicate rows  

---

### 📈 2. Statistical Summary
- Separate numerical & categorical summary  
- Identified unique values and top categories  
- Balanced distributions observed across many features

---

### 🧑‍🤝‍🧑 3. Demographic Insights
- **Avg Age:** 43.47  
- **Age Range:** 18–69  
- **Most Common City:** San Jose  
- **Account Split:** Savings (50.1%) vs Current (49.9%)

---

### 💰 4. Financial Analysis
- **Avg Account Balance:** $5,060  
- **Avg Loan Amount:** $25,501  
- **Avg Credit Limit:** $5,549  
- **Most Common Loan Type:** Mortgage  
- **Most Common Card:** MasterCard  

Visuals include:  
✔ Account balance distribution  
✔ Loan amount distribution  
✔ Credit limit spread  
✔ Transaction amount histogram  
✔ Card & loan type frequency charts  

---

### 🔄 5. Transaction Analysis
- 3 major transaction types: Deposit, Withdrawal, Transfer  
- **604 negative balance occurrences**  
- Transaction amounts analyzed by type (boxplots)  

---

### 🏛 6. Loan Portfolio Analysis
- Loan status distribution (Approved / Closed / Rejected)  
- **Avg Interest Rate:** 5.51%  
- **Avg Loan Term:** 36.5 months  
- **Loan Approval Rate:** 34.2%  

---

### 🧮 7. Correlation Analysis
- Full heatmap of numerical correlations  
- Strong correlations observed between ID-based columns (CustomerID ↔ CardID ↔ LoanID)  
- Top 10 correlation pairs reported  

---

### ⚠️ 8. Anomaly Detection
- **4700 normal** vs **300 anomalous** records  
- Comparison of anomalies vs normal customers on:
  - Account Balance  
  - Transaction Amount  
  - Loan Amount  
  - Age  

---

📝 Conclusion

This project provides a holistic, modular, and scalable banking EDA framework.
It gives insights into customer behavior, financial patterns, loan operations, anomalies, and correlations — forming a strong base for feature engineering and predictive modeling.


