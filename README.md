# 📊 Data Career & Professional Survey — Power BI Dashboard

## 📌 Project Overview
An end-to-end Business Intelligence project analyzing career demographics, salary benchmarks, programming language adoption, and workplace satisfaction from a survey of 630+ data professionals.

---

## 📸 Dashboard Preview

---

## 🛠️ Tech Stack & Skills
* **BI Tool:** Microsoft Power BI Desktop
* **Data Transformation (ETL):** Power Query (M Language)
* **Visualizations:** Cards (KPIs), Treemap, Clustered Bar Charts, Gauges, Pie Charts
* **Concepts:** Data Cleaning, Delimiter Parsing, Categorical Normalization, Dataviz UX

---

## 🔄 Data Preparation & ETL Workflow (Power Query)
* **String Normalization:** Cleared free-text responses for job titles and programming languages by parsing leftmost delimiters.
* **Range Extraction:** Converted raw compensation ranges (e.g., "$106k-125k") into numeric values by splitting by digit-to-non-digit steps, replacing outliers (`+`), and calculating an average benchmark value.
* **Data Type Integrity:** Re-cast text columns into whole/decimal numbers to allow mathematical aggregations on salaries and satisfaction ratings.

---

## 📈 Key Insights
* **Salary Distribution:** Data Scientists and Data Engineers reported the highest average compensation bands among respondents.
* **Tool Popularity:** Python remains the most widely cited primary programming language across data roles.
* **Work-Life vs. Salary Sentiment:** Gauges indicate a higher average satisfaction score for work-life balance compared to compensation levels.

---

## 📂 Repository Contents
* `Data_Survey_Dashboard.pbix` — Full interactive Power BI report file.
* `dashboard_preview.png` — High-resolution dashboard screenshot.
* `Power_BI_Final_Project.xlsx` — Raw survey source data.
