
---

# 📦 Smart Inventory & Sales Analytics Dashboard

> **A Power BI Dashboard for Understanding Inventory Management Challenges, Operational Inefficiencies, and AI Readiness Among Small Businesses**

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi\&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Cleaning-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📖 Table of Contents

* [Project Overview](#-Project-Overview)
* 
* [Project Objectives](#-Project-Objectives)
* 
* [Business Problem](#-Business-Problem)
* 
* [Research Questions](#-Research-Questions)
* 
* [Dataset Information](#-Dataset-Information)
* 
* [Tools and Technologies](#-Tools-and-Technologies)
* 
* [Data Cleaning Process](#-Data-Cleaning-Process)
* 
* [Data Modeling](#-Data-Modeling)
* 
* [DAX Measures](#-DAX-Measures)
* 
* [Dashboard Pages](#-Dashboard-Pages)
* 
* [Key Insights](#-Key-Insights)
* 
* [Business Recommendations](#-Business-Recommendations)
* 
* [Challenges Encountered](#-Challenges-Encountered)
* 
* [Future Improvements](#-Future-Improvements)
* 
* [Project Files](#-Project-Files)
* 
* [Author](#-Author)

---

# 📌 Project Overview

Small businesses often struggle with inventory management due to manual tracking processes, delayed stock updates, reconciliation issues, and limited visibility into inventory performance.

This project presents an interactive **Power BI dashboard** developed as part of a collaborative **Smart Inventory & Sales Tracker Capstone Project By Group7**. The dashboard transforms survey responses into meaningful business insights, helping stakeholders understand operational challenges, inventory practices, and readiness to adopt AI-powered inventory solutions.

---

# 🎯 Project Objectives

The dashboard was designed to:

* Analyze how businesses currently manage inventory.
* Identify the most common inventory management challenges.
* Measure the level of dependence on manual inventory processes.
* Evaluate business readiness for AI-assisted inventory management.
* Provide actionable recommendations for improving inventory operations.

---

# 💼 Business Problem

Many small businesses continue to rely on manual inventory systems, making it difficult to:

* Monitor stock levels accurately.
* Reduce inventory discrepancies.
* Prevent stock shortages and overstocking.
* Reconcile sales with physical inventory.
* Generate timely inventory reports.
* Make informed business decisions.

Without real-time inventory insights, businesses risk operational inefficiencies, increased costs, and poor customer satisfaction.

---

# ❓ Research Questions

This dashboard answers the following questions:

1. What are the key inventory management challenges faced by businesses?
2. Which inventory tracking methods are most commonly used?
3. How much time is spent managing inventory manually each week?
4. Which devices are commonly used for inventory operations?
5. Which dashboard insights are most valuable to business owners?
6. How ready are businesses to adopt AI-powered inventory assistants?
7. Which inventory improvements should be prioritized?

---

# 📊 Dataset Information

**Source:** Google Forms Survey

**Respondents:** 41 Business Owners and Inventory Managers

The dataset includes information on:

* Inventory tracking methods
* Inventory management hours
* Devices used
* Inventory issue frequency
* Inventory update methods
* Reconciliation challenges
* Preferred inventory alerts
* Desired dashboard insights
* AI adoption readiness
* AI-related business questions

---

# 🛠 Tools and Technologies

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel / CSV
* GitHub

---

# 🧹 Data Cleaning Process

Data preparation was completed using **Power Query**.

The following transformations were performed:

* Renamed lengthy survey questions into meaningful field names.
* Removed unnecessary columns.
* Trimmed and cleaned text values.
* Converted inventory hour ranges into numerical values for KPI calculations.
* Created a Business Size category based on SKU ranges.
* Standardized AI adoption responses.
* Split multiple-selection responses where appropriate.
* Corrected inconsistent text formatting.

---

# 📈 Data Modeling

A simplified star-style model was implemented using cleaned survey data.

Additional calculated columns and measures were created to improve reporting and dashboard interactivity.

Examples include:

* Business_Size
* Inventory_Hours_Num
* Average Inventory Hours
* AI Ready %
* Manual Tracking %
* Inventory Issue %
* Total Respondents

---

# 📐 DAX Measures

Key measures developed include:

* Total Respondents
* Average Inventory Hours
* AI Ready %
* Manual Tracking %
* Inventory Issue %

These measures power KPI cards and support dynamic filtering throughout the dashboard.

---

# 📊 Dashboard Pages

## 📄 Page 1 — Executive Overview

Provides a high-level summary of inventory operations through:

* KPI Cards
* Inventory Tracking Method Distribution
* Devices Used
* Business Size Distribution
* Interactive Filters
* Executive Summary
<img width="1366" height="758" alt="smart inventory page 1" src="https://github.com/user-attachments/assets/757fcff7-4b75-494d-89b9-5d0a66c28b47" />

---

## 📄 Page 2 — Inventory Challenges

Highlights operational challenges including:

* Inventory Issue Frequency
* Reconciliation Challenges
* Manual Inventory Practices
* Operational Insights
<img width="1354" height="639" alt="smart inventory page 2" src="https://github.com/user-attachments/assets/235d1ffb-5f11-450a-a63a-ecb110435e29" />

---

## 📄 Page 3 — AI Readiness & Smart Features

Explores business interest in AI-driven inventory management through:

* AI Adoption Rate
* Preferred Alert Methods
* Requested Dashboard Features
* Smart Inventory Opportunities
<img width="978" height="630" alt="smart inventory page 3" src="https://github.com/user-attachments/assets/87c0406f-c392-4abf-9034-4efd58bfcc0a" />

---

## 📄 Page 4 — Strategic Recommendations

Provides practical recommendations based on survey findings, including:

* Inventory Automation
* Smart Alerts
* AI Inventory Assistant
* Demand Forecasting
<img width="960" height="534" alt="smart inventory page 4" src="https://github.com/user-attachments/assets/00da2113-b6b0-4207-a377-6827d863a468" />

---

# 🔍 Key Insights

The analysis revealed several important findings:

* Many businesses continue to rely on manual inventory tracking methods.
* Manual inventory processes consume several hours each week.
* Inventory discrepancies remain a recurring operational challenge.
* Business owners expressed strong interest in AI-powered inventory assistants.
* Demand forecasting and smart alerts were identified as highly valuable features.
* Businesses are increasingly open to adopting intelligent inventory management systems.

---

# 💡 Business Recommendations

Based on the findings, the following recommendations are proposed:

* Automate inventory tracking processes.
* Implement real-time stock alerts.
* Introduce AI-powered inventory assistants.
* Adopt demand forecasting to improve stock planning.
* Improve inventory reporting through interactive dashboards.
* Reduce manual reconciliation using digital inventory systems.

---

# ⚠ Challenges Encountered

Several challenges were encountered during the project:

* Cleaning lengthy Google Forms survey questions.
* Standardizing inconsistent text responses.
* Processing multiple-selection survey responses.
* Converting categorical hour ranges into numerical values.
* Designing KPIs from survey-based data.
* Creating a visually engaging dashboard while maintaining readability.

---

# 🚀 Future Improvements

Future versions of the dashboard could include:

* Live inventory database integration.
* SQL Server connectivity.
* Real-time inventory monitoring.
* Predictive inventory forecasting using Machine Learning.
* Automated email and SMS stock alerts.
* Mobile-responsive Power BI reporting.
* Role-based dashboard access for business users.

---

# 📁 Project Files

```
📦 Smart-Inventory-Sales-Analytics
│
├── Data
│   ├── Smart Inventory Survey.csv
│
├── Dashboard
│   ├── Smart Inventory Dashboard.pbix
│   ├── Dashboard Screenshots
│
├── Images
│
├── README.md
│
└── LICENSE
```

---

# 👨‍💻 Author

## **Maduabuchi Goodness Chidera**

**Role:** Data Analyst | Power BI Developer

### Responsibilities

* Survey Data Analysis
* Data Cleaning (Power Query)
* Data Modeling
* DAX Development
* Dashboard Design
* Data Visualization
* Business Insights
* Strategic Recommendations

---

# ⭐ If you found this project interesting, feel free to star the repository and connect with me on LinkedIn!

---

