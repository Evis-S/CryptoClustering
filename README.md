# Crypto Clustering

In this assignment, I aim to predict whether cryptocurrencies are affected by 24-hour or 7-day price changes. I utilized our knowledge of Python and unsupervised learning techniques.

*Data Preparation
To normalize the data from the CSV file, I employed the StandardScaler() module from scikit-learn and created a DataFrame.
![Alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/evisssaliaj/Desktop/Screenshot%202023-07-11%20at%204.33.25%20PM.png?version%3D1689107961196)

*Finding the Best Value for k Using the Original Scaled DataFrame
I determined the optimal value for k by analyzing the Elbow curve.
![Alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/evisssaliaj/Desktop/bokeh_plot.png?version%3D1689108471718)


*Clustering Cryptocurrencies with K-means Using the Original Scaled Data

Using the original scaled data, I performed clustering using the K-means algorithm to group the cryptocurrencies.

*Optimizing Clusters with Principal Component Analysis
I employed Principal Component Analysis (PCA) to optimize the clusters.
![Alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/evisssaliaj/Desktop/Screenshot%202023-07-11%20at%204.33.41%20PM.png?version%3D1689108229932)

*Finding the Best Value for k Using the PCA Data
I identified the best value for k by analyzing the data transformed using PCA.


![Alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/evisssaliaj/Desktop/Composite%20Elbow%20curves.png?version%3D1689108361812![Alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/evisssaliaj/Desktop/Composite%20scatter%20plots%20.png?version%3D1689107935042))

