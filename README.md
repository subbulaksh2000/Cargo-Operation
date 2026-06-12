# 🚢 Cargo Operations Analytics Dashboard using Power BI and Microsoft Fabric

<p align="center">

### Power BI • Microsoft Fabric • DAX • Dataflow Gen2 • Lakehouse • PL-300 • DP-600 • Interactive Analytics

Transforming cargo movement data into operational insights through interactive business intelligence and modern Microsoft Fabric analytics architecture.

</p>

---

# 📌 Project Overview

The **Cargo Operations Analytics Dashboard** is an end-to-end Business Intelligence solution developed using **Microsoft Power BI** as part of **PL-300 (Microsoft Power BI Data Analyst)** preparation and portfolio development.

This dashboard enables users to monitor cargo movement performance, evaluate operational efficiency, identify trends, and support data-driven decisions through interactive analytics.

The project is also being enhanced with **Microsoft Fabric concepts**, including **Dataflow Gen2, Fabric Lakehouse, Data Pipelines, Semantic Model, and Direct Lake**. This helps demonstrate how a Power BI dashboard can be extended into a modern, scalable, and enterprise-ready analytics solution.

---

# ✨ Dashboard Highlights

✅ Executive KPI Monitoring
✅ Cargo Trend Analysis
✅ Terminal Performance Ranking
✅ Vessel Category Insights
✅ Time Intelligence — YTD / MoM / Running Total
✅ Interactive Filtering & Navigation
✅ Microsoft Fabric Architecture
✅ Lakehouse-Based Data Storage Concept
✅ Dataflow Gen2 Transformation Planning
✅ Automated Pipeline Workflow

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
* Support faster operational decision-making

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
* Analyse performance changes over time
* Support data-driven decision-making

---

# 🏗 Microsoft Fabric Architecture

This project can be extended using Microsoft Fabric to create a more complete analytics solution.

```text
Raw Cargo Operations Data
        ↓
Microsoft Fabric Dataflow Gen2
        ↓
Fabric Lakehouse
        ↓
Power BI Semantic Model
        ↓
Power BI Dashboard
        ↓
Business Insights
```

---

# 🧩 Microsoft Fabric Features Added / Proposed

| Fabric Feature         | Purpose in This Project                                              |
| ---------------------- | -------------------------------------------------------------------- |
| Dataflow Gen2          | Cleans, transforms, and prepares raw cargo operations data           |
| Fabric Lakehouse       | Stores cleaned cargo, terminal, vessel, and time-based data          |
| Data Pipeline          | Automates data ingestion, transformation, and refresh workflow       |
| Semantic Model         | Creates a reusable business reporting layer for Power BI             |
| Direct Lake            | Supports faster reporting from Lakehouse tables                      |
| Power BI Report        | Provides interactive dashboard and KPI analysis                      |
| Real-Time Intelligence | Future enhancement for live cargo monitoring and alerts              |
| Deployment Pipeline    | Future enhancement for development, testing, and production workflow |

---

# 🔄 Proposed Fabric Data Workflow

```text
1. Raw cargo data is collected from CSV, Excel, or operational systems
2. Dataflow Gen2 is used to clean and transform the data
3. Cleaned tables are stored in a Fabric Lakehouse
4. A semantic model is created using fact and dimension tables
5. DAX measures are added for KPI calculations
6. Power BI dashboard visualises cargo performance insights
7. Data Pipeline automates refresh and reporting workflow
```

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

| Table                | Purpose                                                                                                |
| -------------------- | ------------------------------------------------------------------------------------------------------ |
| fact_cargo_movements | Stores cargo movement records, container counts, movement duration, terminal, vessel, and time details |

---

## Dimension Tables

| Table        | Purpose                                                                             |
| ------------ | ----------------------------------------------------------------------------------- |
| dim_time     | Supports time intelligence calculations such as YTD, MoM growth, and running totals |
| dim_terminal | Supports terminal-level performance analysis                                        |
| dim_vessel   | Supports vessel category and vessel movement insights                               |

---

# 📊 Dashboard Pages

## 🏠 Page 1 — Executive Overview

### KPIs

* Total Containers
* Total Movements
* Average Move Duration
* Containers per Movement

### Visualisations

* Container Trends
* Terminal Comparison
* Regional Analysis
* Vessel Distribution
* KPI Cards

---

## 📈 Page 2 — Performance Analytics

### KPIs

* Containers YTD
* Running Containers
* MoM Growth %
* Terminal Ranking

### Visualisations

* Treemap
* Ranking Table
* Trend Analysis
* Performance Tracking
* Terminal Performance Comparison

---

# 🧠 Business Questions Answered

✔ Which region handles the highest cargo volume?
✔ Which terminal performs best?
✔ Which vessel category contributes most?
✔ How are operations changing over time?
✔ What is the month-over-month cargo growth?
✔ Which terminals require performance review?
✔ How can Microsoft Fabric improve reporting scalability and automation?

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
| KPI Cards         | ✅           |
| Trend Analysis    | ✅           |

---

# 🧵 Microsoft Fabric Skills Demonstrated

| Skill Area           | Description                                                |
| -------------------- | ---------------------------------------------------------- |
| Data Ingestion       | Understanding how raw cargo data can be loaded into Fabric |
| Data Transformation  | Planning data preparation using Dataflow Gen2              |
| Lakehouse Design     | Structuring cleaned data in a Fabric Lakehouse             |
| Semantic Modelling   | Creating fact and dimension tables for Power BI reporting  |
| Pipeline Automation  | Designing automated refresh workflows using Data Pipelines |
| BI Reporting         | Building interactive dashboards in Power BI                |
| Enterprise Analytics | Connecting reporting with scalable Fabric architecture     |

---

# 📘 Documentation

### DAX Measures Documentation

📄 [View DAX Measures Documentation](./DAX%20Measures%20Documentation.pdf)

---

# 🛠 Technology Stack

```text
Power BI Desktop
Microsoft Fabric
Dataflow Gen2
Fabric Lakehouse
Data Pipelines
Power BI Semantic Model
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
* Data Modelling
* Time Intelligence
* Microsoft Fabric Architecture
* Dataflow Gen2 Concepts
* Lakehouse-Based Analytics
* Pipeline Automation
* PL-300 Exam Preparation
* DP-600 Fabric Learning Preparation

---

# 💼 Career Relevance

This project is relevant to roles such as:

* Data Analyst
* Power BI Developer
* Business Intelligence Analyst
* Analytics Intern
* Reporting Analyst
* Microsoft Fabric Analyst
* Junior Data Engineer

This project is also useful for internship preparation where **Microsoft Fabric, Power BI, data modelling, reporting, and analytics skills** are required.

---

# 🚀 Future Enhancements

Planned future improvements include:

* Build the Lakehouse layer directly in Microsoft Fabric
* Create Dataflow Gen2 transformations for the cargo dataset
* Automate refresh using Fabric Data Pipelines
* Create a Direct Lake semantic model
* Publish the report to Power BI Service
* Add Row-Level Security for different business users
* Add forecasting for cargo movement trends
* Add anomaly detection for unusual cargo activity
* Add Real-Time Intelligence for live cargo delay alerts
* Create deployment pipeline for development, testing, and production environments

---

# 📁 Repository Structure

```text
Cargo-Operations-Analytics-Dashboard/
│
├── README.md
├── Cargo operation dash.pbix
├── DAX Measures Documentation.pdf
│
├── Screenshot/
│   ├── Cargo Operation Analytics Dashboard .jpg
│   └── Performance Analytics Dashboard.jpg
│
└── fabric/
    ├── architecture.md
    ├── dataflow-gen2-notes.md
    ├── lakehouse-design.md
    └── pipeline-workflow.md
```

---

# ✅ Project Status

Current status: **In Progress**

Completed:

* Power BI dashboard structure
* Executive Overview page
* Performance Analytics page
* KPI visuals
* DAX measures
* Dashboard navigation
* Dashboard screenshots
* README documentation

In progress:

* Microsoft Fabric architecture enhancement
* Dataflow Gen2 planning
* Lakehouse design
* Pipeline workflow documentation
* Portfolio-ready project explanation

---

# 👩‍💻 Author

**Subbulakshmi Natarajan**
Master of Data Science Graduate
Power BI | Microsoft Fabric | Data Analytics | Business Intelligence | Data Governance

---

# 📌 Summary

This project demonstrates how cargo operations data can be transformed into meaningful business insights using Power BI and Microsoft Fabric concepts.

By combining dashboard reporting with modern analytics architecture such as Dataflow Gen2, Fabric Lakehouse, Data Pipelines, Semantic Model, and Direct Lake, this project reflects a more practical and industry-aligned approach to business intelligence.

