# Crypto_Clustering

## Purpose
Utilize clustering methods to identify if 24 hour and 7 day price changes affect the prediction of cryptocurrency pricing.

##Preperation
Use StandardScaler to standardize the the data and use tickers as the index.

## KMeans
Identified the optimal cluster by running the KMeans ranging from 1-10 then graphing using the elbow method
Using the original scaled data, KMeans was preformed on 4 clusters then added the predictions to the dataframe and graphed. 

The results showed outliers creating the other clusters.

##Pca
To lower the features and strengthen the result, used PCA to create 3 features to represent the data. 
With three features, PC1 holds the most importance since the variance ratio shows PC1 composing of 97.6% of the data's influence
