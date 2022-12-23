# Cryptocurrencies
## Overview
In this project, Unsupervised Machine Learning was enabled to analyze multiple cryptocurrenices in order to advise in investment strategies. Popular cryptocurrencies, such as BitCoin, have done well in the market and prices have soared. For new investers wanting to break into the crypto market it may be more affordable to consider alternative options. In this project we can take a closer look at any possible trends in order to make a more informed investment in alternative coins. 

Methods used for analysis:

  * Preprocessing data
  * Reducing the data dimension using Principal Component Analysis
  * Clustering cryptocurrencies using K-Means
  * Visualizing classification results with 2D and 3D scatter plots

## Results
After preprocessing and cleaning our dataset we are left with 532 tradable cryptocurrencies.

**K-means Clustering Algorithm, Elbow Curve:**
Producing an elbow curve using the K-Means method to identify clusters. The k value shows to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

![elbow_curve](https://user-images.githubusercontent.com/110632671/209294597-300c6156-0c12-467b-af1f-89c4dc76ff53.png)

***Cryptocurrencies Results Visualizations***
### 3D Scatterplot with Clusters
The 3D scatter plot located each clustered crypto in relation to the 3 principal components using the PCA algorithm. As shown, there are 3 major groups and one outlier.

![3d_scatterplot](https://user-images.githubusercontent.com/110632671/209295927-747daf72-89e3-413b-bf03-95570decbeac.png)

### 2D Scatterplot with Clusters
This 2-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to two principal components. When graphing the clustered cryptos by total supply and mined coins, we can observe two outliers and the distribution and the four clusters of cryptocurrencies. 

![2D_Scatter](https://user-images.githubusercontent.com/110632671/209296949-7ff16cea-68f0-4090-8e76-5851369dc0fd.png)

## Conlusion
Unsupervised Machine Learning is used to discover patterns in data before any known outcome. This analysis was succesful in finding those patterns. However, now that those patterns have been discovered more analysis can be done on the four groups to determine performance of each coin. 



