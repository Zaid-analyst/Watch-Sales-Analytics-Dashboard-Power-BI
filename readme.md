# Watch Sales Analytics Dashboard | Power BI

## Overview

The Watch Sales Analytics Dashboard is an end-to-end Business Intelligence project developed using Microsoft Power BI. The objective of this project is to transform raw watch sales data into actionable insights through data modeling, DAX calculations, and interactive visualizations.

The solution follows a Star Schema data model consisting of one Fact table and multiple Dimension tables, enabling efficient analysis across products, customers, and time dimensions. This project demonstrates core data analytics skills including data modeling, KPI development, business analysis, and dashboard design.

---

## Business Problem

Organizations selling watches across multiple brands and categories require a centralized analytics solution to monitor sales performance, customer behavior, product trends, and revenue growth.

This dashboard helps stakeholders answer key business questions such as:

* Which watch brands generate the highest revenue?
* Which product categories perform best?
* What customer segments contribute most to sales?
* How do sales trends change over time?
* What are the major revenue drivers across products and customers?

---

## Project Objectives

* Design a scalable Star Schema data model.
* Create meaningful KPIs using DAX.
* Analyze sales performance across multiple business dimensions.
* Deliver actionable insights through interactive dashboards.
* Enable data-driven decision-making for management teams.

---

## Data Model

### Fact Table

**Fact_Sales**

* Sale_ID
* Customer_Key
* Product_Key
* Date_Key
* Quantity
* Revenue

### Dimension Tables

**Dim_Product**

* Product_Key
* Watch_Brand
* Watch_Category
* Product_Name

**Dim_Customer**

* Customer_Key
* Gender
* Age_Group
* Customer_Segment

**Dim_Date**

* Date_Key
* Date
* Month
* Quarter
* Year

---

## Key Performance Indicators (KPIs)

### Sales KPIs

* Total Revenue
* Total Sales
* Total Quantity Sold
* Average Selling Price

### Customer KPIs

* Total Customers
* Revenue per Customer
* Customer Segment Contribution

### Product KPIs

* Best Performing Brand
* Best Performing Category
* Product Revenue Contribution

### Time Intelligence KPIs

* Previous Year Revenue
* Year-over-Year Growth
* Running Revenue

---

## Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of overall business performance.

Visuals:

* Revenue Trend
* Revenue by Brand
* Revenue by Category
* Monthly Sales Trend

### 2. Product Performance Analysis

Focuses on product-level performance metrics.

Visuals:

* Revenue by Brand
* Quantity Sold by Brand
* Revenue by Category
* Top Products Analysis

### 3. Customer Analysis

Analyzes customer demographics and purchasing behavior.

Visuals:

* Revenue by Gender
* Revenue by Age Group
* Revenue by Customer Segment
* Customer Distribution

### 4. Time Intelligence Analysis

Evaluates sales performance over different periods.

Visuals:

* Revenue by Year
* Revenue by Quarter
* Revenue by Month
* Running Revenue Trend

### 5. Brand Performance Analysis

Provides deep insights into watch brand performance.

Visuals:

* Brand Revenue Ranking
* Brand Market Share
* Brand Contribution Analysis

### 6. Category Performance Analysis

Evaluates performance across watch categories.

Visuals:

* Category Revenue Analysis
* Category Share Analysis
* Category Trends

### 7. Business Insights & Summary

Summarizes major findings and business recommendations.

Visuals:

* Top Revenue Brands
* Top Revenue Categories
* Top Customer Segments
* Revenue Distribution

---

## Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Star Schema Data Modeling
* Data Visualization
* Business Intelligence Reporting

---

## Skills Demonstrated

* Data Cleaning and Transformation
* Data Modeling
* Star Schema Design
* DAX Measure Development
* KPI Design
* Dashboard Development
* Business Analysis
* Data Storytelling
* Insight Generation

---

## Key Business Insights

* Identified top-performing watch brands and categories.
* Analyzed customer purchasing patterns.
* Evaluated sales performance trends over time.
* Measured revenue contribution across different business segments.
* Generated actionable insights to support strategic decision-making.

---

## Portfolio Information

**Project Title:** Watch Sales Analytics Dashboard

**Role:** Data Analyst

**Developed By:** Zaid Shaikh

**GitHub Username:** Zaid-Analyst

**Project Type:** End-to-End Power BI Analytics Project

---

## Contact

GitHub: https://github.com/Zaid-Analyst

For collaboration, feedback, or project discussions, feel free to connect through GitHub.
