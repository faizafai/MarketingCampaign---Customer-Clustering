# Customer Personality Analysis and Clustering Project

## Overview

This project involves analyzing the Customer Personality Analysis dataset from Kaggle which you can [visit here](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/data), which contains information on customer behavior and demographics. 
The goal was to understand customer segments and profiles to better tailor marketing strategies.

## Dataset Description

The dataset includes attributes such as:
- **Demographics**: Age, Income, Marital Status, Education, etc.
- **Purchase Behavior**: Number of purchases, web visits, and deals accepted.
- **Marketing Data**: Amount spent on different product categories.

## Project Steps

### 1. Data Cleaning
- Handled missing values and outliers.
- Handled duplicate rows.
- Cleaned abnormal/inconsistent/anomalous rows.

### 2. Feature Engineering
- Added new columns: Age, Spent, Children, Partner, Family, Has_Kids, and Customer_Duration_Years.

### 3. Data preprocessing
- Converted categorical data into numerical data using StandardScaler.
- Applied Principal Component Analysis (PCA) to reduce dimensionality.

### 4. Clustering
- Determined the optimal number of clusters using the KElbowVisualizer.
- Clustered the data and profiled customers based on key attributes: education, age, income, spending, number of children, family size, and customer duration.

## Results
- Identified distinct customer segments with unique profiles, aiding in personalized marketing strategies.
