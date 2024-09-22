
# E-commerce Customer Segmentation

## Overview

This project aims to perform customer segmentation for an e-commerce platform using various machine learning techniques. The analysis includes data preprocessing, clustering, and visualization to gain insights into customer behavior.

## Contents

- **Data Sources**: The project uses data from multiple Excel sheets:
  - `customers`: Contains customer details such as ID, join date, city, and gender.
  - `genders`: Maps gender IDs to gender names.
  - `cities`: Maps city IDs to city names.
  - `transactions`: Contains transaction records with details like transaction ID, customer ID, date, and status.
  - `branches`: Contains branch IDs and associated merchant IDs.
  - `merchants`: Maps merchant IDs to merchant names.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Ipywidgets

## processes 
- load data
- data exploration and cleaning
- feature selection
- EDA
- model building
- model Evalution
- segment analysis
  
## Data Preprocessing
- Loading Data: Use libraries like Pandas to read Excel files and load data into DataFrames.
- Cleaning Data: Handle missing values, correct data types, and remove duplicates to ensure data quality.
- Feature Engineering: select best fit & important feature

## Exploratory Data Analysis (EDA):
- Visualizations: Use Matplotlib and Seaborn to visualize distributions and relationships within the data. This helps identify trends and patterns.

## Clustering:
- KMeans Clustering: Segment customers into distinct groups based on their purchasing behaviors.
                     Determine the optimal number of clusters using methods like the Elbow Method or Silhouette Score.
- DBSCAN: Use density-based clustering to find clusters of varying shapes and sizes, which is useful for identifying outliers.
- Agglomerative Clustering: Another hierarchical method for clustering that can provide insights into the relationships between different customer groups.

## Model Evaluation:
- Use metrics such as Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Index to evaluate the quality of the clusters formed.

## Insights Extraction:
from using the RFM techniques we could segment the customers into groups based on the (last time they shopping , the money they spend , how many times they do ) 
also used many model techniques to cluster te customers into groups , so we could target the canpagian and understand the customers purchasing pattern .
