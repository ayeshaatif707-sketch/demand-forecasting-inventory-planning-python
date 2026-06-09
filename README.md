# Demand Forecasting & Inventory Planning Using Python

## Overview

This project demonstrates a complete business analytics workflow for demand forecasting, inventory planning, and automated reporting using Python.

The solution analyzes over 900,000 sales records, forecasts future demand using Facebook Prophet, calculates inventory planning metrics, and automatically generates Excel and PDF management reports.

---

## Business Problem

Businesses frequently struggle with:

* Inventory shortages
* Overstocking
* Poor demand visibility
* Manual reporting processes
* Inefficient replenishment decisions

This project addresses these challenges through forecasting and inventory planning automation.

---

## Dataset

Store Item Demand Forecasting Dataset

Dataset Characteristics:

* 913,000 sales records
* 10 stores
* 50 products
* Daily sales history
* 5 years of transaction data

Columns:

* Date
* Store
* Item
* Sales

---

## Project Workflow

### 1. Data Preparation

* Data loading
* Data cleaning
* Date feature engineering
* Exploratory analysis

### 2. Business Analytics

* Sales trend analysis
* Store performance analysis
* Product performance analysis
* KPI generation

### 3. Demand Forecasting

Forecasting model:

* Facebook Prophet

Evaluation metrics:

* MAE
* MAPE
* R² Score

Results:

| Metric | Value   |
| ------ | ------- |
| MAE    | 1486.77 |
| MAPE   | 5.62%   |
| R²     | 0.925   |

---

## Inventory Planning

Calculated metrics:

### Average Daily Demand

24,582 units

### Safety Stock

28,019 units

### Reorder Point

200,095 units

Inventory recommendations are generated automatically based on forecasted demand patterns.

---

## Automated Reporting

### Excel Report

Generated automatically with:

* Executive Summary
* Forecast Metrics
* Inventory Planning
* Recommendations

### PDF Report

Management-ready report containing:

* KPI Summary
* Forecast Results
* Demand Analysis
* Inventory Recommendations
* Visualizations

---

## Visualizations

Generated dashboards include:

* Daily Sales Trend
* Monthly Sales Trend
* Store Performance
* Top Products Analysis
* Actual vs Forecast
* 90-Day Forecast
* Inventory Risk Dashboard

---

## Technologies Used

### Programming

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Prophet
* OpenPyXL
* ReportLab
* Scikit-learn

---

## Key Outcomes

* Automated business reporting
* Demand forecasting
* Inventory planning
* Reorder point optimization
* Executive dashboard generation
* PDF and Excel report automation

---

## Author

Ayesha Atif

Python Automation | Data Analytics | Demand Forecasting | Inventory Planning
