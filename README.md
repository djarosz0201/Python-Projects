# Python Data Analysis Final Project: Business Performance & Sales Insights

## Project Overview
This repository contains the final project for the Python module of a Data Analyst course. The primary goal of the project is to clean raw data, perform comprehensive exploratory data analysis (EDA), and derive actionable business insights regarding sales performance, delivery efficiency, and customer behavior.

---

## Project Stages & Key Tasks

### 1. Data Exploration & Understanding
* Loaded and inspected datasets across multiple tables.
* Identified key primary and foreign keys used to relationalize and merge the data.

### 2. Data Cleaning & Preprocessing
* **Missing Values:** Assessed missing data proportions and handled them with justified imputation or removal strategies.
* **Data Types:** Verified and converted data types to ensure consistency.
* **Duplicates & Anomalies:** Cleaned data by resolving hidden issues such as extra whitespaces, case inconsistencies, and character similarities (e.g., Cyrillic vs. Latin scripts).

### 3. Exploratory Data Analysis & Visualization
* **Data Integration:** Merged three separate tables into a single master DataFrame, dropping redundant columns and renaming fields for clarity.
* **Core KPIs:** Calculated high-level business metrics such as total orders, total profit, and active markets.
* **Sales Performance:** Analyzed revenues, expenses, profits, and product popularity across product categories, geographic locations (countries/regions), and sales channels (online vs. physical).
* **Logistics & Delivery Analysis:** Examined the time gap between order placement and shipping across different segments.
* **Profitability vs. Delivery Time:** Investigated correlations between delivery speed and overall profitability.
* **Sales Trends & Seasonality:** Analyzed sales dynamics over time and by day of the week (using `day_name()`) to detect seasonal patterns.

### 4. Reporting
* Compiled a detailed report within a Google Colab notebook featuring clean code, data visualizations, and strategic business conclusions.

---

## Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Cleaning:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab

---
