# Cryptocurrencies

## Overview

Utilizing unsupervised machine learning techniques to determine with crypocurrencies are on the trading market and which would be best for investing and make a recommendation for an investment group. As there is no know output, unsupervised machine learning is preferred over a supervised machine learning method. 

### Software Used
Jupyter Notebook \
Python \
Scikit-learn \
Plotly \
HvPlot


### Results

To complete this project there were 4 steps that needed to be completed. 

1. Preprocess the data
- Show only Coins that are being mined and traded

![image}(minedCrypto)

- Clean data by removing null values, and cryptos without any mined coins

![image](nullValues)

- Retain rows with Mined Coins

![image](MinedCoins)

- Use get_dummies to convert categorical data into dummy or indicator variables

![image](dummyValues)

2. Reduce data dimensions using PCA

- Use the Principal Component Analysis to reduce all factors into desired number of dimensions, which is 4

![image](PCA)

3. Cluster cryptocurriences using K-Means

- Using the elbow curve to predict the values for the clusters

![image](elbow)

- K-means algorithm 

![image](kmeans)

- Create New Dataframe that holds predicted clusted and crypto features

![image](newDataFrame)

4. Visualize Results

- 3D Scatter Plot for PCAs used
![image](3D)
- HvPlot to show all current tradable cryptocurriences

![image](hvplotTable)

- Scatter plt to show "Coins Mined" vs "Total Coin Supply"

![image](hvtplot)



