# Coffee Sales Data Analysis

## Overview

This project analyzes coffee vending machine sales data to extract actionable insights for stock management, customer behavior, and operational efficiency.

The dataset contains transaction-level data including purchase time, payment method, and coffee type, enabling a detailed behavioral and temporal analysis.

---

## Dataset

* Source: Coffee vending machine transactions
* Duration: March 2024 – March 2025
* Features:

  * Date & Time of purchase
  * Payment type (cash/card)
  * Transaction amount
  * Coffee type

---

## Key Insights

* **Top Products:** Latte and Americano with Milk dominate sales across all customer segments.
* **Customer Behavior:** A small group of heavy users contributes disproportionately to revenue.
* **Peak Demand Periods:** Sales spikes occur around October and February rather than consistent seasonal peaks.
* **Weekly Trends:** Tuesday shows the highest sales, while Sunday has the lowest demand.
* **Time Patterns:** Demand varies significantly by time of day, with routine-driven weekday consumption.
* **Stock Strategy:** Core items must always be prioritized due to consistent high demand.

---

## Business Recommendations

* Refill machines **weekly** instead of monthly
* Schedule maintenance on **Sunday (low demand day)**
* Perform restocking during **night hours**
* Prioritize inventory:

  1. Latte
  2. Americano with Milk
  3. Americano
* Avoid stockouts of core products to prevent revenue loss

---

## Customer Segmentation

Customers were categorized based on purchase frequency:

* One-time users
* Occasional users
* Regular users
* Heavy users

**Insight:** Heavy users, though fewer, generate significant revenue — retention is critical.

---

## Analysis Performed

* Data Cleaning & Preprocessing
* Monthly & Seasonal Trend Analysis
* Customer Segmentation
* Weekly & Daily Sales Analysis
* Time-of-Day Behavior Analysis
* Product Demand Analysis

---

## Project Structure

* `data/` → Raw datasets
* `notebook/` → Jupyter Notebook with analysis
* `report/` → Final PDF report

---

## Tools Used

* Python
* Pandas
* Matplotlib / Seaborn

---

## Key Takeaway

This project demonstrates how structured data analysis can drive real-world operational decisions such as inventory planning, demand forecasting, and customer retention — without relying on complex machine learning models.
