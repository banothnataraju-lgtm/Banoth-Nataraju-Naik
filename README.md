# Bank Analytics Project

## 📘 Project Overview

This project focuses on analyzing bank loan and transaction data using **Excel, SQL, Power BI, and Tableau**. The goal is to identify trends in loan disbursement, recovery rates, and customer demographics to provide data-driven insights for banking decisions.

---

## 🧩 Tools & Technologies Used

* **Microsoft Excel** – Data cleaning and initial exploration
* **SQL** – Querying and analyzing structured bank data
* **Power BI** – Building interactive dashboards for insights
* **Tableau** – Visual storytelling and trend analysis

---

## 📊 Power BI Dashboard

Here’s a preview of my interactive Power BI dashboard analyzing bank loans and recoveries:

![Bank Analytics Dashboard]()

**Key Insights:**

* Loan distribution by **religion**, **caste**, and **age group**
* **State-wise** and **region-wise** loan performance
* Key KPIs: *Total Loan Amount, Total Collection, Total Interest, Delinquent Loans Rate*
* Visual filters for year, purpose, and grade segmentation

---

## 📈 Excel Dashboard

An Excel-based dashboard highlighting:

* Total Payments, Interest, Funded & Loan Amounts
* Regional and Age-wise summaries
* Loan recovery analysis using charts and pivot tables

![Excel Dashboard]()

---

## 🗄️ SQL Analysis

Sample SQL queries used in the analysis:

```sql
-- Total Loan Amount Funded
SELECT SUM(`Funded Amount`) AS Total_Loan_Funded
FROM bank_data;

-- Total Interest Collected
SELECT SUM(`Interest Amount`) AS Total_Interest
FROM bank_data;

-- Region-wise Loan Distribution
SELECT Region, SUM(`Loan Amount`) AS Total_Loan
FROM bank_data
GROUP BY Region;
```

---

## 📉 Tableau Dashboard

Created a Tableau dashboard for deeper insights and visual storytelling:

* Loan trends across states
* Recovery rate comparison
* Interactive filters for loan type and borrower category

---

## 🧠 Key Learnings

* Improved understanding of **data cleaning** and **data modeling**
* Built skills in **visual analytics** using Power BI and Tableau
* Learned to **integrate SQL outputs** into dashboards
* Experience gained from **Data Analyst Internship at AI Variant**

---

## 🏁 Conclusion

This Bank Analytics project demonstrates how business insights can be extracted from financial data using modern analytics tools. The interactive dashboards support better decision-making in the banking sector.

---

### 👤 Author

**Banoth Nataraju Naik**
Data Analyst | Excel | Power BI | Tableau | SQL
📧 [banoth.nataraju@gmail.com]
🌍 [(https://github.com/banothnataraju-lgtm)]
