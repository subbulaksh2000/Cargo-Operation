# 🚢 Cargo Operations Analytics Dashboard

<p align="center">

### Power BI • DAX • PL-300 • Interactive Analytics

Transforming cargo movement data into operational insights through interactive business intelligence.

</p>

---

# 📌 Project Overview

The **Cargo Operations Analytics Dashboard** is an end-to-end Business Intelligence solution developed using **Microsoft Power BI** as part of **PL-300 (Microsoft Power BI Data Analyst)** preparation and portfolio development.

This dashboard enables users to monitor cargo movement performance, evaluate operational efficiency, identify trends, and support data-driven decisions through interactive analytics.

---

# ✨ Dashboard Highlights

✅ Executive KPI Monitoring
✅ Cargo Trend Analysis
✅ Terminal Performance Ranking
✅ Vessel Category Insights
✅ Time Intelligence (YTD / MoM / Running Total)
✅ Interactive Filtering & Navigation

---

# 🖼 Dashboard Preview

## 📊 Executive Overview

![Executive Dashboard](./Screenshot/Cargo%20Operation%20Analytics%20Dashboard%20.jpg)

### Overview

Provides a high-level operational summary of cargo movement activities.

### KPIs Included

* Total Containers
* Total Movements
* Average Move Duration
* Containers per Movement

### Business Insights

* Monitor operational workload
* Compare terminal performance
* Analyse regional activity
* Track movement trends

---

## 📈 Performance Analytics

![Performance Dashboard](./Screenshot/Performance%20Analytics%20Dashboard.jpg)

### Overview

Supports deeper operational performance evaluation and business insights.

### KPIs Included

* Containers YTD
* Running Containers
* Month-over-Month Growth %
* Terminal Ranking

### Business Insights

* Evaluate operational growth
* Track cumulative performance
* Identify top-performing terminals
* Support data-driven decision making

---

# 📂 Dataset Architecture

```text
fact_cargo_movements
      │
 ┌────┼────┐
 │    │    │
dim_time
dim_terminal
dim_vessel
```

---

## Fact Table

| Table                |
| -------------------- |
| fact_cargo_movements |

---

## Dimension Tables

| Table        | Purpose           |
| ------------ | ----------------- |
| dim_time     | Time Intelligence |
| dim_terminal | Terminal Analysis |
| dim_vessel   | Vessel Insights   |

---

# 📊 Dashboard Pages

## 🏠 Page 1 — Executive Overview

### KPIs

* Total Containers
* Total Movements
* Average Move Duration

### Visualisations

* Container Trends
* Terminal Comparison
* Regional Analysis
* Vessel Distribution

---

## 📈 Page 2 — Performance Analytics

### KPIs

* Containers YTD
* Running Containers
* MoM Growth %

### Visualisations

* Treemap
* Ranking Table
* Trend Analysis
* Performance Tracking

---

# 🧠 Business Questions Answered

✔ Which region handles the highest cargo volume?
✔ Which terminal performs best?
✔ Which vessel category contributes most?
✔ How are operations changing over time?

---

# ⚙️ Power BI Features Implemented

| Category          | Implemented |
| ----------------- | ----------- |
| Power Query       | ✅           |
| Data Modelling    | ✅           |
| DAX Measures      | ✅           |
| Time Intelligence | ✅           |
| Drillthrough      | ✅           |
| Tooltips          | ✅           |
| Bookmarks         | ✅           |
| Navigation        | ✅           |

---

# 📘 Documentation

### DAX Measures Documentation

📄 [View DAX Measures Documentation](./DAX%20Measures%20Documentation.pdf)

---

# 🛠 Technology Stack

```text
Power BI Desktop
DAX
Power Query
Data Modelling
Business Analytics
```

---

# 🎯 Learning Outcomes

This project strengthened practical understanding of:

* Dashboard Design
* KPI Development
* Data Storytelling
* DAX Calculations
* Business Intelligence Concepts
* PL-300 Exam Preparation

---

# 👩‍💻 Developed By

### Subbulakshmi Natarajan

Power BI • Data Analytics • Business Intelligence
