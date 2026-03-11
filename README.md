# SMART-CART
Smart Cart is a intelligent customer segmentation system using unsupervised learning .
This system will analyse historical customer transaction data and group customers into meaningful clusters based on purchasing behaviour,engagment levels and loyalty indicators.
Smart Cart uses clustering algorithms to discover hidden patterns in customer behaviour and support data driven decision making .

# Working of Project

In this project we uses a dataset which contain the customers data and the attributes like demographics,purchase behaviour,website activity and response are also included in this dataset.

1.Read the dataset.

2.Get dataset info using pandas library.

3.Handle the missing value.

4.perform Feature Enginerring to derive some more information.

5.visualize the data based on different attributes to see the outliers in the dataset and also plot the heatmaps to check for the correlation.

Heatmaps results that Income and Spending are dependended on each other 

6.Encoding of categorical data.

7.standardization for numerical data.

8.Performed PCA

9.TO find the number of cluster we used Elbow method and silhouette score 
Here K value is 4 hence, we can conclude that total 4 types of customer.

10.Then we have used two clustering methods to get these 4 clusters 
1 K-MEANS Clustering 
2 Agglomerative 

11.Then we have derived some informations from these clusters such as 
Which clusters have more customers
Understand the total spending and Income of each clusters

# Conclusion 
Finally get the cluster summary and we can conclude that out of 4 clusters 2 clusters have high income compared to rest of the 2 cluster.

High income clusters have more total spending ,more purchase and purchases are more from store  than from website that's why website visit of these clusters are less while less income clusters

But the tenure of all the clusters are almost same 

# Result 
1. To Target High Income customer we can increase the store,
2. To Target Low Income Customer we can have  discounts ,offers on website purchase .

It can effectively increase our total purchase from SMART CART


