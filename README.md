# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes **3,900 customer purchase transactions** to uncover meaningful insights into customer behavior, spending patterns, and product performance.

The objective is to support strategic business decisions through structured data analysis using **Python, SQL, and Power BI**.

---

## Dataset Summary

- **Total Transactions:** 3,900
- **Total Features:** 18
- **Locations Covered:** 50
- **Unique Products:** 25
- **Product Categories:** Clothing, Accessories, Footwear, Outerwear

The dataset includes customer demographics, purchase details, subscription status, shipping preferences, and review ratings.

---

## Project Workflow

### 1. Data Preparation (Python)

- Loaded and explored dataset using Pandas
- Cleaned missing values (37 records handled)
- Standardized column names
- Performed feature engineering:
  - Created `age_group`
  - Created `purchase_frequency_days`
- Integrated cleaned dataset with PostgreSQL

---

### 2. SQL Business Analysis

Performed structured queries to answer key business questions:

- Revenue comparison by gender
- Customer segmentation analysis
- Subscriber vs. non-subscriber behavior
- Revenue by product category
- Sales performance by age group
- Discount usage patterns

---

### 3. Power BI Dashboard

Developed an interactive dashboard to visualize key metrics:

- **Total Customers:** 4,000
- **Average Purchase Amount:** $59.76
- **Average Review Rating:** 3.75
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Subscription Status Distribution

---

## Key Insights

### Revenue Distribution

- Male customers contribute **68%** of total revenue
- Female customers contribute **32%**

### Customer Segmentation

- Loyal Customers: **80%**
- Returning Customers: **18%**
- New Customers: **2%**

Loyal customers form the primary revenue base.

### Category Performance

- Clothing generates the highest revenue
- Accessories follow as the second strongest category

### Subscription Analysis

- Only **27%** of customers are subscribers
- **73%** represent potential conversion opportunity

---

## Strategic Recommendations

- Increase subscription conversion initiatives
- Strengthen loyalty programs
- Optimize discount strategies
- Promote high-rated products
- Target high-performing customer segments

---

## Tools & Technologies

- Python (Pandas, NumPy)
- PostgreSQL
- Power BI
- Git & GitHub
