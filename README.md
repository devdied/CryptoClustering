# CryptoClustering
 
 In this project I used Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. This code applies K-Means and Principal Component Analysis (PCA) to cluster cryptocurrencies based on performance over 7 different holding periods.

The analysis could be replicable to other financial series, with large amount of data thanks to the use of PCA, which reduces the dimentionality of the data.

The analysis found the same number and composition of clusters (4) when using the original standarized data of 7 series of returns than when using its 3 principal components. These three principal components explained 90% of the variance of the cryptocurrencies' returns.