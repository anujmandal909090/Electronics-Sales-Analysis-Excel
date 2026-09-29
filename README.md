# 📊 Electronics Sales Analysis — Excel

## 📌 Project Overview

This project analyzes an electronics sales dataset using **Microsoft Excel**.

The workbook is structured into four main sheets:

- Raw_Data
- KPI
- Pivot Table
- Dashboard

The analysis focuses on sales value, order volume, quantity sold, customer ratings, delivery performance, product categories, states, payment methods, and order status.

## 🎯 Project Objectives

- Prepare and validate the sales dataset for analysis.
- Create summary KPIs to understand overall business performance.
- Analyze sales across products, states, payment modes, order status, and customer gender.
- Build an interactive Excel dashboard.
- Identify useful business patterns and data-quality issues.

## 📂 Dataset

The dataset contains **5,017 transaction rows and 14 columns**.

Key fields include:

- Order ID
- Order Status
- Device Name
- Category
- Company
- Price
- Quantity
- State
- Gender
- Age
- Rating
- Payment Mode
- Warranty

## 🧹 Data Cleaning & Quality Checks

The analysis identified several data-quality points:

- 1,270 rating values are blank.
- 17 repeated Order ID values were identified.
- Some categorical fields contain `Unknown` values.
- Some labels have inconsistent spacing and capitalization.
- The dataset contains 5,017 data rows, while the workbook's Total Orders KPI displays 5,018 because the `COUNTA` formula includes the header cell.

These checks are important because duplicate identifiers, missing values, and inconsistent labels can affect analysis results.

## 📈 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | 95,950,267 |
| Total Orders | 5,018 |
| Total Quantity Sold | 8,615 |
| Average Order Value | 19,125.03 |
| Average Rating | 3 |
| Delivery Rate | 43.6% |

> Note: KPI values are documented as implemented in the original workbook.

## 🔄 Excel Analysis Workflow

### Raw_Data
Contains the source transaction-level dataset.

### KPI
Contains formula-based summary metrics.

### Pivot Table
Provides grouped analysis across major business dimensions.

### Dashboard
Presents KPIs and analysis visually using charts and interactive filters.

## 📊 Dashboard

The Excel dashboard provides a visual summary of the sales data using KPI cards, charts, and interactive filters.


## 🔍 Pivot Table Analysis

The Pivot Table analysis provides insights across products, states, payment modes, order status, and gender.

Some observations from the workbook:

- Laptop has the largest summed Price value among the standardized product labels.
- Camera and TV are also major contributors.
- Kerala has the highest state-level summed Price value among the states shown.
- Credit Card and Cash are the two most frequent payment modes.
- Delivered is the most frequent order-status category.
- Male customers form the largest gender group in the current dataset.

## 💡 Key Business Insights

- The workbook reports a total Price value of **95.95 million**.
- The dataset contains **8,615 units** in the Quantity field.
- Delivered orders account for approximately **43.6%** according to the workbook's delivery-rate calculation.
- Laptop is the strongest product category by summed Price.
- Camera and TV are also significant contributors.
- Credit Card and Cash are the major payment modes.
- Missing ratings, Unknown values, repeated Order IDs, and inconsistent labels should be considered before using the analysis for operational decision-making.

