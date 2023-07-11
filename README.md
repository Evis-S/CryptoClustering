# Crypto Clustering

In this assignment, I aim to predict whether cryptocurrencies are affected by 24-hour or 7-day price changes. I utilized our knowledge of Python and unsupervised learning techniques.

*Data Preparation
To normalize the data from the CSV file, I employed the StandardScaler() module from scikit-learn and created a DataFrame.

*Finding the Best Value for k Using the Original Scaled DataFrame

I determined the optimal value for k by analyzing the Elbow curve.

*Clustering Cryptocurrencies with K-means Using the Original Scaled Data

Using the original scaled data, I performed clustering using the K-means algorithm to group the cryptocurrencies.

*Optimizing Clusters with Principal Component Analysis
I employed Principal Component Analysis (PCA) to optimize the clusters.

*Finding the Best Value for k Using the PCA Data

I identified the best value for k by analyzing the data transformed using PCA.