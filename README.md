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

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/minedCrypto.png)

- Clean data by removing null values, and cryptos without any mined coins

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/nullValues.png)

- Retain rows with Mined Coins

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/MinedCoins.png)

- Use get_dummies to convert categorical data into dummy or indicator variables

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/dummyValues.png)

2. Reduce data dimensions using PCA

- Use the Principal Component Analysis to reduce all factors into desired number of dimensions, which is 4

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/PCA.png)

3. Cluster cryptocurriences using K-Means

- Using the elbow curve to predict the values for the clusters

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/elbow.png)

- K-means algorithm 

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/kmeans.png)

- Create New Dataframe that holds predicted clusters and crypto features

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/newDataFrame.png)

4. Visualize Results

- 3D Scatter Plot for PCAs used
![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/3D.png)
- HvPlot to show all current tradable cryptocurriences

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/hvplotTable.png)

- Scatter plot to show "Coins Mined" vs "Total Coin Supply"

![image](https://github.com/roderickspells/Cryptocurrencies/blob/main/Challenge/images/hvtplot.png)



