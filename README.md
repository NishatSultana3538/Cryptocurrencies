# Cryptocurrencies
## Overview of Analysis:
The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:

* Preprocessing the database,
* Reducing the data dimension using Principal Component Analysis,
* Clustering cryptocurrencies using K-Means,
* Visualizing classification results with 2D and 3D scatter plots.

## Clustering Cryptocurrencies using K-Means - Elbow Curve

We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

![elbow_curve](https://github.com/NishatSultana3538/Cryptocurrencies/blob/main/image/elbow.png)

## Visualizing Cryptocurrencies Results
### 3D-Scatter plot with clusters

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

![3D PLOT](https://github.com/NishatSultana3538/Cryptocurrencies/blob/main/image/hvplot.png)



### Tradable Cryptocurrencies Table

![table](https://github.com/NishatSultana3538/Cryptocurrencies/blob/main/image/tradable_crypto_table.png)

### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply

![2D PLOT](https://github.com/NishatSultana3538/Cryptocurrencies/blob/main/image/scatterplot.png)

## Summary

We have identified the classification of 532 cryptocurrencies based on similarities of their features. 