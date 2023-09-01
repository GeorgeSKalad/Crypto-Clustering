# Cryptocurrency Cluster Analysis using K-Means

This repository contains Python code for performing cluster analysis on cryptocurrency market data using the K-Means algorithm. 
The analysis is performed using both the original data and data reduced through Principal Component Analysis (PCA). The goal is to explore the impact of using fewer features on the clustering results.

## Prerequisites
Before running the code, ensure you have the following installed:
- Python 
- Jupyter Notebook
- Required Python libraries (Pandas, hvPlot, scikit-learn)

## Code Overview

- The `cluster_analysis.ipynb` notebook contains the Python code for data loading, preprocessing, visualization, K-Means clustering, and cluster visualization.
- The code demonstrates how to analyze cryptocurrency market data using both the original feature set and PCA-reduced data.
- Elbow curves are used to determine the optimal number of clusters (`k`).

## Results

The analysis yields the following insights:

- Elbow curves show the optimal `k` values as 4 for the original data and 3 for PCA-reduced data.
- Cluster visualization plots display how cryptocurrencies are grouped based on selected features.
- The cluster patterns and the optimal `k` values differ between the original data and PCA-reduced data, highlighting the impact of using fewer features on clustering results.

## Conclusion

Using fewer features through PCA alters the clustering dynamics and can lead to different insights into the data. This analysis demonstrates the trade-offs between simplifying analysis and retaining original data characteristics.


