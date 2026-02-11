# pharmaceutical-sales-bi-dashboard
End-to-end Power BI dashboard for pharmaceutical sales analysis (186K+ transactions), including star schema modeling, KPI design, target variance analysis, customer retention analytics, and AI-driven key influencer insights.


---

# Pharmaceutical Sales Business Intelligence Dashboard

### End-to-End Power BI Analytics Project



## 📌 Project Overview

This project presents a comprehensive **Business Intelligence dashboard** developed in **Power BI** to analyze pharmaceutical sales performance over a three-year period.

The dataset contains more than **186,000 sales transactions**, along with target planning data, customer information, geographic hierarchy, and product classifications. The objective of this project is to transform raw transactional data into actionable business insights that support strategic and operational decision-making.

This solution includes:

* Dimensional data modeling (Star Schema)
* KPI design and performance measurement
* Target vs. Actual variance analysis
* Customer segmentation and retention analytics
* Geographic sales analysis
* AI-powered Key Influencers analysis



## 🏗 Data Model Architecture

The project follows a **Star Schema** design for optimal performance and analytical clarity.

### Fact Tables

* **Sales**
* **Target**

### Dimension Tables

* Calendar
* Products
* Companies (Brands)
* Pharmacies
* Distributors
* Cities
* Provinces

### Key Modeling Features

* Proper one-to-many relationships
* Calendar table marked as Date Table
* Time-intelligence enabled (YTD, trend analysis)
* Clean referential integrity across all foreign keys
* Hierarchical geography (Province → City)

This structure ensures scalability, performance efficiency, and accurate aggregations.



## 📊 Dataset Summary

| Table        | Records |
| ------------ | ------- |
| Sales        | 186,304 |
| Target       | 56,910  |
| Pharmacies   | 18,038  |
| Cities       | 977     |
| Provinces    | 31      |
| Products     | 67      |
| Companies    | 3       |
| Distributors | 13      |

Time Range:
**March 2020 – June 2022**



## 📈 KPIs Implemented

### Sales Performance

* Total Sales (ResultPack)
* Total Packs Sold
* Sales by Brand
* Sales by Product Category
* Sales Trend Over Time
* Sales by Province & City

### Target Analysis

* Total Target
* Achievement %
* Variance (Actual – Target)
* Product-Level Target Performance
* Regional Target Deviation

### Customer Analytics

* New Customers
* Returning Customers
* Lost Customers
* Retention Rate
* Purchase Frequency
* Customer Lifetime Sales



## 📊 Dashboard Structure

The report contains five analytical pages:



### 1️⃣ Sales Overview

High-level executive summary including:

* Brand-level performance
* Time-based sales trends
* Product contribution analysis
* Actual vs Target comparison
* Interactive filters (Product, Distributor, Province, Date)

Purpose: Provide management with a strategic performance snapshot.



### 2️⃣ Provincial Sales Analysis

Geographical performance evaluation:

* Map visualization (Province-level)
* Regional sales trend analysis
* Top-performing cities per province
* Drill-down capability (Province → City)

Purpose: Identify regional strengths and growth opportunities.



### 3️⃣ Target vs Sales Performance

Performance monitoring against predefined goals:

* Time-based Actual vs Target comparison
* Variance analysis visualization
* Product-level performance matrix
* Over-performance and under-performance tracking

Purpose: Evaluate execution efficiency and planning accuracy.



### 4️⃣ Customer Analysis

Customer behavior and retention insights:

* Customer segmentation (New / Returning / Lost)
* Retention trend over time
* Purchase frequency distribution
* Behavioral pattern analysis

Purpose: Understand customer lifecycle and revenue sustainability.



### 5️⃣ Customer Detail (Drill-Through)

Granular pharmacy-level insights:

* Individual customer sales volume
* Purchase history timeline
* Product preferences
* Customer classification

Purpose: Enable micro-level sales strategy evaluation.



## 🤖 AI-Driven Analysis

The project integrates **Power BI Key Influencers visual** to identify the most impactful drivers behind:

* High sales performance
* Target achievement
* Customer retention

Variables evaluated include:

* Product category
* Distributor
* Geographic location
* Brand
* Purchase behavior

All AI-generated insights were critically evaluated and interpreted to ensure business relevance.



## 🧠 Business Insights Derived

This dashboard enables the identification of:

* Regions consistently outperforming targets
* Product groups with strongest retention impact
* Distributors associated with higher sales growth
* Seasonal sales patterns
* Customer churn risk indicators

If deployed in a real pharmaceutical company, this solution could:

* Improve regional resource allocation
* Optimize distributor strategy
* Enhance customer retention programs
* Increase target achievement accuracy



## 🛠 Technical Skills Demonstrated

* Power BI Data Modeling
* Star Schema Design
* DAX Measures Development
* Time Intelligence Functions
* Variance Analysis
* Customer Segmentation Logic
* AI-Based Analytical Visualization
* Business Insight Communication



## 🎯 Project Type

Academic Business Intelligence Project
Designed to simulate a real-world pharmaceutical sales analytics environment.



## 🚀 Potential Enhancements

Future improvements could include:

* Cohort Analysis
* Predictive Sales Modeling
* RFM Segmentation
* Forecasting Integration
* Deployment to Power BI Service



## 📎 Author

Developed by: **Farzad Mohseni**
