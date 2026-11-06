# Bank Loan Reporting & Performance Analysis (Power BI & SQL Server)

A comprehensive end-to-end data analytics project built to track, monitor, and evaluate bank loan performance, financial metrics, borrower repayment trends, and performance scores using SQL Server and Power BI.

---

## 📌 Project Overview
This project is designed to analyze a financial institution's lending portfolio to extract actionable insights. Using **SQL Server (`SOUL/SQLEXPRESS` instance / `Bank LoanDB`)** for data extraction and SQL queries, combined with **Power BI** for dynamic visualizations, this project tracks overall loan portfolio health, total disbursements, recovery rates, and comprehensive performance scores.

---

## 📊 Key Performance Indicators (KPIs), Scores & Detailed Metrics

### 1. Loan Application Metrics & Volume Scores
* **Total Loan Applications:** Tracking the overall volume of loan applications received.
* **Month-to-Date (MTD) Loan Applications:** Monitoring current month application numbers.
* **Month-over-Month (MoM) Growth Score:** Evaluating application growth velocity and trends compared to previous periods.

### 2. Funding & Financial Disbursal Metrics
* **Total Funded Amount:** Total capital disbursed by the bank to borrowers.
* **MTD Funded Amount:** Capital disbursed specifically in the current month.
* **Total Amount Received:** Total cash recovered and collected from borrowers against funded loans.
* **MTD Amount Received:** Recovery collections tracked for the current month.

### 3. Risk, Health & Borrower Profile Scores
* **Average Interest Rate Score:** Portfolio-wide average interest rates charged on loans.
* **Average Debt-to-Income (DTI) Ratio Score:** Assessing borrower financial stability, debt burdens, and repayment capacity.

### 4. Good Loan vs. Bad Loan Performance & Ratio Scores
* **Good Loan Performance Scores:** 
  * Good Loan Percentage & Application Count.
  * Good Loan Funded Amount vs. Total Amount Received.
* **Bad Loan Performance Scores (Non-Performing Assets - NPAs):** 
  * Bad Loan Percentage & Application Count (loans classified as defaulted or past due).
  * Bad Loan Funded Amount vs. Amount Recovered.

---

## 🛠️ Tech Stack & Tools Used
* **Database & Querying:** SQL Server Management Studio (SSMS), SQL Server (`SOUL/SQLEXPRESS` -> `Bank LoanDB`), Complex SQL Queries.
* **Data Transformation & Modeling:** Power Query, DAX measures (Data Analysis Expressions).
* **Visualization:** Power BI Desktop (`.pbix`), Interactive Slicers, KPI Cards, Bar/Line Charts, Map Visuals.
* **Presentation & Documentation:** PowerPoint (`.pptx`) for project summarization.
* **Version Control:** Git & GitHub.

---

## 📂 Repository Structure & Files
* `BANK LOAN REPORT DASHBOARD.pbix` — The main interactive Power BI dashboard file.
* `financial_loan.csv` — The core dataset containing application details, loan amounts, and repayment statuses.
* `Bank Loan Report PPT Power Bl.pptx` — Presentation deck outlining project objectives and analytical findings.

---

## 🚀 Business Value & Insights
* **Risk Mitigation & Scoring:** Helps risk management teams instantly spot high concentrations of bad loans and monitor average DTI and interest rate scores.
* **Executive Summary:** Provides leadership with a clear view of monthly fund dispatches and cash recovery performance.
* **Operational Efficiency:** Streamlines data processing from SQL Server directly into automated Power BI dashboards.
