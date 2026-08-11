# SmartCart Customer Segmentation

An end-to-end **unsupervised machine learning project** that transforms e-commerce customer data into actionable behavioural segments using **K-Means clustering**.

The project combines data preprocessing, feature engineering, exploratory data analysis, dimensionality reduction, clustering, cluster validation, and business interpretation to support personalised marketing and customer retention strategies.

---

## 📌 Project Overview

SmartCart is a growing e-commerce platform with customer data covering demographics, purchasing behaviour, website activity, recency, complaints, and campaign response.

The business currently uses generic marketing and engagement strategies without clearly understanding different customer behaviour patterns. This can lead to inefficient marketing, missed opportunities to retain high-value customers, and delayed identification of low-engagement customers.

The objective of this project is to build an **intelligent customer segmentation system** using unsupervised machine learning.

The system discovers hidden patterns in customer behaviour and groups customers into meaningful segments that can support:

- Personalised marketing
- Customer retention
- High-value customer identification
- Customer re-engagement
- Promotion targeting
- Channel-specific marketing strategies

---

## 🎯 Business Problem

A one-size-fits-all marketing strategy assumes that all customers behave similarly.

However, customers can differ significantly in:

- Spending
- Purchase frequency
- Product preferences
- Website engagement
- Discount usage
- Purchase channels
- Recency
- Income
- Household characteristics

The key business question is:

> **Can we identify distinct customer segments based on behavioural and demographic characteristics and translate those segments into actionable marketing strategies?**

---

## 🧠 Machine Learning Approach

This project follows an end-to-end unsupervised learning pipeline:

```text
Raw Customer Data
        ↓
Data Quality Audit
        ↓
Missing Value Treatment
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Outlier Handling
        ↓
Categorical Encoding
        ↓
Feature Scaling
        ↓
PCA for Visualization
        ↓
K Selection
        ↓
K-Means Clustering
        ↓
Cluster Validation
        ↓
Cluster Profiling
        ↓
Business Interpretation
