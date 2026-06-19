# Customer Segmentation using K-Means Clustering & RFM Analysis

## Overview
An end-to-end customer segmentation project using RFM 
(Recency, Frequency, Monetary) analysis and K-Means 
clustering to group 2,240 customers into 4 distinct 
behavioral profiles for targeted marketing strategy.

## Objective
- Engineer RFM features to quantify customer behavior
- Segment customers based on demographic and 
  behavioral attributes
- Identify high-value customer groups
- Recommend differentiated marketing strategies 
  per segment

## Customer Segments Identified
- Premium Loyalists — highest income, highest spend
- Affluent Selectives — high income, high purchase frequency
- Emerging Shoppers — mid income, moderate engagement
- Budget Conscious — lower income, price sensitive

## Methodology
### 1. RFM Feature Engineering
- Recency — derived from existing dataset feature
- Frequency — calculated from total purchases across 
  web, catalog, store, and deals channels
- Monetary — calculated from total spend across all 
  product categories

### 2. Data Preprocessing
- Removed datetime columns
- Encoded categorical variables (Education, Marital Status)
- Handled missing values using median imputation
- Standardized features using StandardScaler

### 3. Dimensionality Reduction
- Applied PCA to reduce to 2 components 
  for visualization

### 4. Optimal Cluster Selection
- Used Elbow Method (WCSS) to determine 
  optimal number of clusters
- Selected 4 clusters based on elbow curve

### 5. K-Means Clustering
- Fitted K-Means with 4 clusters
- Mapped clusters to business-relevant segment names 
  based on income and spending patterns

### 6. Cluster Profiling
- Analyzed clusters by Income, Wine Spend, Fruit Spend, 
  Recency, Frequency, and Monetary value
- Validated segment logic against business expectations

## Key Findings
- Premium Loyalists represent the smallest but most 
  valuable segment (175 customers)
- Budget Conscious is the largest segment (1,018 customers), 
  representing price-sensitive volume buyers
- Clear income-spend correlation observed across segments, 
  supporting differentiated marketing strategy

## Tools & Technologies
- Python 3.x
- Pandas — data manipulation
- Scikit-learn — StandardScaler, KMeans, PCA
- Matplotlib — data visualization
- Openpyxl — Excel file reading

## Project Structure
├── Customer_Segmentation_using_K_Means_and_RFM.ipynb

├── segmented_customers_output.csv

├── README.md

└── requirements.txt
## Dataset
Public dataset sourced from Kaggle:
https://www.kaggle.com/code/suprithahalesh/marketing-campaign/notebook

## Author
Shreya Verma
Data Analyst | Marketing Analytics | Customer Intelligence
www.linkedin.com/in/shreyav05
