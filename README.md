
# Cryptocurrency Clustering Project

## Introduction

This project aims to cluster cryptocurrencies based on their market performance. We'll use data analysis and machine learning to identify patterns and relationships in the crypto market.

## Steps

1. **Data Exploration**:
   - Load the market data.
   - View summary statistics and visualize the data.

2. **Data Preparation**:
   - Normalize the data using the `StandardScaler`.
   - Create a new DataFrame with scaled data.

3. **Original Data Analysis**:
   - Use the elbow method to find the best value for k (number of clusters) for the original data.
   - Cluster cryptocurrencies with K-Means on the original data.

4. **Principal Component Analysis (PCA)**:
   - Perform PCA to reduce features to three principal components.
   - Find the best k using PCA data.
   - Cluster cryptocurrencies with K-Means on PCA data.

5. **Results Analysis**:
   - Visualize cluster results and assess the impact of using fewer features.

