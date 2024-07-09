# CryptoClustering

## Overview
This assignment explores the application of unsupervised machine learning techniques to analyse the effects of 24-hour and 7-day price changes on cryptocurrencies.

## Methodology
The analysis pipeline incorporates several data preprocessing and machine learning methods:
- **StandardScaler**: Employed to normalise the dataset, ensuring each feature contributes equitably during the analysis.
- **Elbow Method**:  Used to ascertain the ideal number of clusters by identifying the inflection point in the elbow curve.
- **K-Means Clustering**: Implemented to partition the dataset into clusters, grouping cryptocurrencies based on the similarity of their price change patterns.
- **Principal Component Analysis (PCA)**: Executed to reduce the dataset's dimensionality, preserving core attributes and optimising the clustering outcome.
  
## Results
- The optimal value for `k` was determined using both the original scaled data and the PCA-reduced data, with observations on any differences in the optimal `k` value.
- Clustering was performed using both the original scaled data and the PCA data, with a comparative analysis of the impact of feature reduction on clustering.
  
## Data Visualisation
- Scatter plots were created using hvPlot to visualise clusters for the original scaled data and the PCA data.
  
## Conclusion
The analysis provided insights into the clustering of cryptocurrencies based on price volatility and the influence of dimensionality reduction on the clustering outcomes.

## Source of Data
The dataset was provided by edX Boot Camps LLC.

## Folder Structure
### CryptoClustering (Root Folder)
```
├── Crypto_Clustering.ipynb - Jupyter notebook containing the complete analysis
└── Resources/
      └── crypto_market_data.csv - CSV file with the cryptocurrency market data
```
