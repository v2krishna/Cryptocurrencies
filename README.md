# Cryptocurrencies

## Purpose: The main purpose of the use case is to use Unsupervised machine learning alogrithm to analyze crypto data. We are not sure of the outcome yet for that reason we are using the Unsupervised Alogrithms.
In this analysis we've performed two major alogrithms:
  1. PCA.
  2. K-Means Clustering.

### Following are the steps thats been followed in applying the ML Alogs:
  1. Preprocessing
  2. Reducing the Dimensions using PCA
  3. Clustering using K-Means
  4. Visuzaling

### Technologies:
 * Python3.7 , Anaconda Navigator , Jupyter Notebook
 * Data Source: CryptoData

## Results:

#### Determine the number of Clusters using Elnow - Curve: 
Using the Elbow graph we can determine the number of clusters that the data can be grouped, Based on the below graph and outcome, number of clusters can be determined between 4 & 5 because the horizontal line is around 4 & 5 .
![elbow-curve](/images/01-elbowcurve.PNG)

#### 2-D Scatter Plot ( TotalCoinsMined vs Total Coin Supply):
Using the 2-D Plot  ,we cannot efficiently visualize the classification of the groups, we can try with 3-D scatter plot.

#### 3-D Scatter Plot Visualization:
3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.
![3D-Scatter-Plot-using-PCA](/images/02-scatter-3d_plot.PNG)

#### Tradeable Cryptos:
Below table will help us to the see the data and their classificaiton and also helps to interact with the table.
![tradeable-crypto-table](/images/04-crypto-tradeable-table.PNG)


## Summary:
There are total 532 tradeable crypto's which are classified into 4 categories, based each categories we can analyse the performance of each crypto within their class and recommoned to the clients.


