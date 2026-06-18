# Customer Segmentation using K-Means Clustering

## Overview
An end-to-end customer segmentation project using 
K-Means clustering to group 2,240 customers into 
4 distinct behavioral profiles for targeted 
marketing strategy.

## Objective
- Segment customers based on demographic and 
  behavioral attributes
- Identify high-value customer groups
- Recommend differentiated marketing strategies 
  per segment

## Customer Segments Identified
- Premium Loyalists — high income, high spenders
- Affluent Selectives — high income, selective buyers
- Emerging Shoppers — mid income, growing potential
- Budget Conscious — lower income, price sensitive

## Methodology
### 1. Data Preprocessing
- Removed datetime columns
- Standardized features using StandardScaler

### 2. Dimensionality Reduction
- Applied PCA to reduce to 2 components 
  for visualization

### 3. Optimal Cluster Selection
- Used Elbow Method (WCSS) to determine 
  optimal number of clusters
- Selected 4 clusters based on elbow curve

### 4. K-Means Clustering
- Fitted K-Means with 4 clusters
- Exported segmented customer data to CSV

### 5. Cluster Profiling
- Analyzed clusters by Income, Wine Spend, 
  Fruit Spend, and Recency
- Identified behavioral patterns per segment

## Tools & Technologies
- Python 3.x
- Pandas — data manipulation
- Scikit-learn — StandardScaler, KMeans, PCA
- Matplotlib — cluster visualization
- Openpyxl — Excel file reading
- Tableau — interactive dashboard

## Project Structure
├── Customer_Segmentation_KMeans.ipynb

├── Customer_Segmentation_Dashboard.twb

├── segmented_customers.csv

├── README.md

└── requirements.txt
## Dataset
Public dataset sourced from Kaggle:
https://www.kaggle.com/code/suprithahalesh/
marketing-campaign/notebook

## Note
The Tableau dashboard (.twb file) provides 
interactive visualization of cluster distribution, 
average income per segment, and campaign 
acceptance rates per customer group.

## Author
Shreya Verma
Data Analyst | Marketing Analytics | Customer Intelligence
www.linkedin.com/in/shreyav05
