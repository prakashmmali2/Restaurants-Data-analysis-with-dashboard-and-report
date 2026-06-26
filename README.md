# DoorDash Strategy & Operations Case Study

## Project Overview

This project presents an end-to-end Strategy & Operations analysis of DoorDash marketplace data. The objective is to evaluate operational performance, identify opportunities for improving customer experience, marketplace efficiency, and business performance, and provide data-driven recommendations supported by quantitative analysis.

The analysis follows the DoorDash case study requirements by combining data quality assessment, exploratory data analysis (EDA), KPI development, business insights, and strategic recommendations.

---

# Objectives

- Analyze operational performance across the DoorDash marketplace.
- Evaluate Customer, Dasher, Merchant, and Operations KPIs.
- Identify operational bottlenecks.
- Measure delivery performance.
- Assess regional and temporal demand patterns.
- Recommend actionable business improvements.

---

# Dataset Information

- Source: DoorDash Case Study Dataset
- Analysis Environment: Python (Jupyter Notebook)
- Libraries Used:
  - pandas
  - numpy
  - matplotlib
  - seaborn

---

# Project Workflow

1. Data Loading
2. Data Quality Assessment
3. Data Cleaning
4. Feature Engineering
5. Exploratory Data Analysis
6. KPI Development
7. Business Insights
8. Strategic Recommendations
9. Executive Summary

---

# Data Quality Checks

The dataset was evaluated for:

- Missing values
- Duplicate records
- Data type validation
- Datetime conversion
- Currency formatting
- Outlier detection
- Data consistency

Necessary preprocessing steps were completed before analysis.

---

# Feature Engineering

The following analytical features were created:

- Order Date
- Order Hour
- Weekday
- Weekend Flag
- Meal Period
- Restaurant Preparation Time
- Pickup Time
- Delivery Time
- Total Fulfillment Time
- Tip Indicator

---

# Key Performance Indicators

## Business Performance

| KPI |
|------|
| Total Orders |
| Total Revenue |
| Average Order Value | 
| Discount Percentage |
| Refund Rate |

---

## Customer Experience

| KPI | 
|------|
| Average Delivery Time | 
| Median Delivery Time | 
| 90th Percentile Delivery Time | 
| On-Time Delivery Rate | 
| Average Tip |

---

## Dasher Performance

| KPI |
|------|
| Active Dashers | 
| Orders per Dasher |
| Average Pickup Time |
| Average Delivery Duration |

---

## Merchant Performance

| KPI | 
|------|
| Active Restaurants |
| Orders per Restaurant |
| Average Preparation Time | 
| Top Performing Restaurants |

---

# Visualizations Included

- Missing Value Heatmap
- Distribution of Numerical Features
- Orders by Hour
- Orders by Weekday
- Delivery Time Distribution
- Revenue by Region
- Average Delivery Time by Region
- Top Restaurants by Orders
- Dasher Utilization
- Correlation Matrix

---

# Key Insights

The analysis identified several operational trends:

- Customer demand is concentrated during lunch and dinner peak periods.
- Delivery performance varies across operational regions.
- Restaurant preparation time contributes significantly to overall delivery duration.
- Merchant performance is uneven, with a small number of merchants generating a large share of order volume.
- Discounts and refunds influence overall marketplace profitability and customer experience.

---

# Strategic Recommendations

### 1. Improve Peak-Hour Capacity

- Increase Dasher availability during high-demand periods.
- Introduce targeted incentive programs.
- Improve demand forecasting.

Expected Outcome:
- Reduced delivery time
- Improved on-time delivery rate
- Better customer experience

---

### 2. Optimize Restaurant Operations

- Monitor restaurant preparation performance.
- Share operational scorecards with merchants.
- Improve order preparation workflows.

Expected Outcome:
- Faster order readiness
- Lower fulfillment time
- Improved merchant efficiency

---

### 3. Improve Promotion Effectiveness

- Optimize discount allocation.
- Target promotions using customer behavior.
- Measure promotion ROI regularly.

Expected Outcome:
- Higher marketing efficiency
- Increased profitability
- Better customer retention

---

### 4. Regional Performance Optimization

- Monitor regional delivery KPIs.
- Reallocate Dasher supply dynamically.
- Focus operational support on underperforming regions.

Expected Outcome:
- More consistent marketplace performance
- Reduced regional delivery delays

---

# Assumptions

- All timestamps were converted to the appropriate local timezone.
- Currency values were standardized before analysis.
- Missing records were handled using appropriate preprocessing techniques.
- Outliers were evaluated but retained unless they represented invalid data.
- Analysis reflects only the provided dataset and time period.

---

# Conclusion

This analysis demonstrates a structured Strategy & Operations approach to evaluating DoorDash marketplace performance. By combining operational KPIs, descriptive analytics, and business-focused recommendations, the project identifies opportunities to improve delivery efficiency, customer satisfaction, merchant performance, and overall marketplace effectiveness.

The recommendations prioritize high-impact operational improvements that can be validated through future experimentation and KPI monitoring.

---

# Repository Structure

```
DoorDash-Strategy-Operations/
│
├── DoorDash_Assessment(1).ipynb
├── README.md
├── 2024 Case Study Dataset.csv
├── DoorDash_KPI_Framework.xlsx
└── images/
```

---

# Author

Prakash Mali

Strategy & Operations Case Study
DoorDash
