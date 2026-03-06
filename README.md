# Customer Segmentation using Cohort Analysis & RFM

## Project Overview

This project analyzes **customer purchasing behavior and retention patterns** using **Cohort Analysis and RFM (Recency, Frequency, Monetary) segmentation**.

The objective is to understand **customer lifecycle, identify high-value customer segments, and analyze retention trends** that can support **data-driven business and marketing strategies**.

Customer analytics techniques such as **Cohort Analysis and RFM segmentation** are widely used in industries including **e-commerce, SaaS, fintech, and retail**.

---

# Problem Statement

Businesses often struggle to understand:

- Which customers generate the most revenue  
- How customer purchasing behavior changes over time  
- Which customers are at risk of churning  
- How to identify loyal or high-value customers  

This project aims to answer those questions using **data-driven analysis**.

---

# Dataset

The dataset contains **transactional customer purchase data**, including:

- Customer ID  
- Invoice Date  
- Transaction Amount  
- Purchase Frequency  

The dataset was cleaned and processed before performing analysis.

---

# Tools & Technologies

This project was developed using:

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

# Project Workflow

## 1. Data Understanding

The dataset was first explored to understand its **structure, variables, and potential data quality issues**.

Key steps included:

- Inspect dataset structure  
- Identify missing values  
- Understand transaction patterns  

---

## 2. Data Cleaning & Preprocessing

Data preprocessing steps included:

- Handling missing values  
- Converting date columns into **datetime format**  
- Removing invalid or negative transactions  
- Creating new features for analysis  

Feature engineering was performed to prepare the dataset for **Cohort Analysis and RFM segmentation**.

---

## 3. Exploratory Data Analysis (EDA)

EDA was conducted to explore **customer purchasing patterns**.

Key analysis included:

- Transaction distribution  
- Customer purchase frequency  
- Revenue contribution patterns  

EDA helps identify **trends, anomalies, and patterns in customer behavior**.

---

## 4. Cohort Analysis

Cohort analysis groups customers based on **their first purchase date**.

This allows analysis of **customer retention over time**.

Steps performed:

- Identify each customer's **first purchase month**
- Group customers into **cohorts**
- Calculate **retention rate per cohort**
- Create a **cohort retention table**

This analysis helps businesses understand **customer retention behavior**.

---

## 5. RFM Segmentation

RFM segmentation evaluates customers based on three key metrics:

### Recency
How recently a customer made a purchase.

### Frequency
How often a customer makes purchases.

### Monetary
How much money a customer spends.

Customers are scored and segmented into groups such as:

- High-value customers  
- Loyal customers  
- Potential loyalists  
- At-risk customers  

This segmentation helps businesses **target marketing strategies more effectively**.

---

# Key Insights

From the analysis, several insights were identified:

- A **small percentage of customers contributes a large portion of total revenue**.
- Customer retention **declines significantly after several months**.
- High-value customers tend to have **higher purchase frequency and spending behavior**.

These insights can help businesses:

- Improve **customer retention strategies**
- Identify **high-value customer segments**
- Optimize **marketing campaigns and promotions**

---
