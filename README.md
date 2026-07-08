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

#  E-Commerce Funnel Analysis

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

---

*If you found this project useful or have suggestions, feel free to open an issue or connect with me on LinkedIn.*
