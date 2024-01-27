EastWestAirlines Customer Segmentation
This repository contains Python code for conducting customer segmentation analysis on the EastWestAirlines dataset. The analysis focuses on clustering passengers based on various attributes, including mileage history, accrual, and spending patterns. The primary goal is to identify distinct customer segments using K-means and Hierarchical clustering techniques.

Steps Included:
Data Inspection:

Importing necessary libraries
Reading the EastWestAirlines dataset
Running initial inspection on the data (head, info, describe)
Data Cleaning:

Dropping unnecessary columns (e.g., 'ID')
Checking for and handling missing values
Exploratory Data Analysis (EDA) to understand the distribution and correlation of key variables
Outlier Detection and Removal:

Visualizing outliers using boxplots
Checking if the data follows a Gaussian or non-Gaussian distribution
Removing outliers using the Interquartile Range (IQR) method
Clustering Analysis:

Preparing the data for clustering by scaling and feature selection
Utilizing K-means clustering to identify clusters with optimal silhouette score
Visualizing K-means clusters in a scatterplot
Using Hierarchical clustering with a dendrogram to determine the optimal number of clusters
Visualizing Hierarchical clustering in a scatterplot
Evaluation Metrics:

Calculating Silhouette Score and Calinski-Harabasz Score for both K-means and Hierarchical clustering
Results:

Displaying the cluster counts and means for K-means clustering
Summary of cluster means for K-means clustering
Feel free to explore the provided Jupyter notebook for a detailed walkthrough of the analysis. The insights gained from this segmentation can aid the airline industry in tailoring marketing strategies to specific customer segments, thereby enhancing customer satisfaction and loyalty.
