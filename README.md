# 📊 Internship Projects

A collection of data analysis and visualization projects completed during internship.

## 🗂️ Projects

### 1. Sales Performance Dashboard & Forecast
- **Tool:** Power BI
- **Description:** Interactive dashboard analyzing sales performance with forecasting capabilities.

### 2. Website Data Analysis
- **Tool:** Python (Jupyter Notebook)
- **Description:** Exploratory data analysis of website traffic and user behavior data.

### 3. HR Analytics Dashboard - Attrition Analysis
- **Tool:** Power BI
- **Description:** Interactive dashboard analyzing employee attrition, including breakdowns by job role, department, age group, gender, and business travel.

## 🛠️ Technologies Used
- Python (Pandas, Matplotlib)
- Power BI
- Jupyter Notebook

# 4. E-Commerce Funnel Analysis

An end-to-end funnel analysis project built on a simulated e-commerce user-behavior dataset, covering the full customer journey from **Browse → Add to Cart → Checkout → Purchase**. The project combines Python-based data analysis with interactive Power BI dashboards to uncover where users drop off and why.

## 📌 Project Overview

Using session-level event data, this project:
- Reconstructs each user session from raw event logs
- Identifies the furthest funnel stage reached per session
- Calculates conversion and drop-off rates at each stage
- Breaks down performance by **marketing channel**, **region**, **device type**, and **product category**
- Surfaces revenue metrics (Total Revenue, Average Order Value) tied to funnel performance

## 🧰 Tools & Technologies

- **Python** — pandas, NumPy
- **Visualization** — Matplotlib, Seaborn, Plotly
- **BI Tool** — Power BI (interactive dashboards)
- **Environment** — Jupyter Notebook

## 📊 Dashboards

This project includes three Power BI dashboards:

1. **User Funnel Analysis** — overall funnel shape, stage-by-stage conversion
2. **Funnel Drop-off Diagnostics** — pinpointing exactly where users abandon the journey, broken down by segment
3. **Customer Behavior Insights** — channel, device, region, and product-category performance

*(Add dashboard screenshots here, e.g. `![Dashboard](images/user_funnel_dashboard.png)`)*

## 🔍 Key Insights

- Overall conversion rate (Browse → Purchase): **~10.8%**
- The largest single drop-off occurs at the **Checkout stage** (~50% of users who add an item to cart do not complete checkout)
- Conversion and revenue performance vary meaningfully by **channel**, **device**, and **region**, highlighting where marketing and UX investment would have the highest impact

## 📂 Repository Structure

```
funnel-analysis-project/
├── README.md
├── Funnel_Analysis.ipynb
├── data/
│   └── dataset.csv
├── dashboards/
│   └── funnel_analysis.pbix
└── images/
    └── (dashboard screenshots)
```

## 🚀 How to Run

1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn plotly`
3. Open `Funnel_Analysis.ipynb` in Jupyter Notebook/Lab
4. Run all cells to reproduce the analysis
5. Open `dashboards/funnel_analysis.pbix` in Power BI Desktop to explore the interactive dashboards

## 📝 Note

The dataset used in this project is a **generated/synthetic dataset** created for practice and portfolio purposes, and does not represent real company data.


# 5․🏦 Bank Loan Report | Power BI Dashboard

An interactive Power BI dashboard for analyzing a bank's loan portfolio — tracking loan applications, funded amounts, repayment performance, and risk indicators across multiple dimensions.

## 📊 Overview

This project transforms raw loan-level data into a decision-ready dashboard, helping stakeholders quickly assess portfolio health, identify risk concentrations, and monitor lending performance over time.

The report is built across **3 pages**:
- **Summary** — high-level KPIs and Good vs. Bad Loan breakdown
- **Overview** — trend analysis and month-over-month comparisons
- **Details** — granular, filterable loan-level data

## ✨ Key Features

- **Core KPIs**: Total Loan Applications, Total Funded Amount, Total Amount Received, Average Interest Rate, Average DTI (Debt-to-Income)
- **MTD / MoM tracking**: Month-to-date values alongside month-over-month growth for every key metric
- **Good vs. Bad Loan analysis**: Loans classified as "Good" (Fully Paid, Current) vs. "Bad" (Charged Off), with side-by-side comparison of application counts, funded amounts, and amounts received
- **Loan Status breakdown table**: Full metrics segmented by status (Fully Paid, Current, Charged Off)
- **Dynamic filtering**: Slice the report by State, Grade, and Loan Purpose
- **DAX-driven measures**: All KPIs built with reusable, well-structured DAX measures rather than static calculations

## 🛠️ Tools & Techniques

- **Power BI Desktop** — report design and data modeling
- **DAX** — `CALCULATE`, `DIVIDE`, `FILTER`, and custom measures for KPIs and ratios
- **Data Modeling** — structured relationships and calculated columns/groups (e.g., Good vs. Bad Loan classification)
- **SQL** — exploratory queries used to validate metrics (e.g., Good Loan %, MTD/PMTD Avg DTI) independently of the Power BI model

## 📁 Key Metrics Explained

| Metric | Description |
|---|---|
| **Total Loan Applications** | Total number of loan applications submitted |
| **Total Funded Amount** | Total dollar amount disbursed across all loans |
| **Total Amount Received** | Total dollar amount collected/repaid so far |
| **Good Loan %** | Share of loans classified as Fully Paid or Current |
| **Avg Interest Rate** | Average interest rate across the portfolio |
| **Avg DTI** | Average Debt-to-Income ratio of borrowers — the share of a borrower's monthly income going toward debt payments (across all their debts, not just this bank's loan) |

## 🚀 How to Use

1. Clone or download this repository
2. Open `Bank Loan Report.pbix` in Power BI Desktop
3. Refresh the data source if needed (Home → Refresh)
4. Explore the report using the page tabs (Summary / Overview / Details) and the State, Grade, and Purpose filters

## 📌 Notes

This project was built as a portfolio piece to demonstrate skills in:
- Financial/lending KPI design
- DAX measure development
- Interactive dashboard storytelling
- Data validation using SQL

---

Feel free to explore, fork, or reach out with feedback!

---

*If you found this project useful or have suggestions, feel free to open an issue or connect with me on [LinkedIn](https://www.linkedin.com/in/raisa-melkumian-8a4ab0238/.)*
