# CryptoClustering

This project applies unsupervised learning to analyze cryptocurrency data, predicting clustering based on price changes using K-Means and Principal Component Analysis (PCA).

# Files
Crypto_Clustering.ipynb: Main Jupyter notebook containing the clustering analysis.

crypto_market_data.csv: The dataset containing cryptocurrency data.

# Steps Taken
Data Preprocessing: Scaled the data using StandardScaler.

K-Means Clustering: Used K-Means to group cryptocurrencies based on price changes.

PCA Optimization: Reduced dimensions using PCA and re-applied K-Means.

Elbow Method: Identified the optimal number of clusters (k) using inertia values.

Visualizations: Generated scatter plots and elbow curves for comparison.

# Requirements
- Python 3

- Pandas

- Scikit-learn

- hvplot

