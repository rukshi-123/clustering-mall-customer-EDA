fqeuhr## clustering-mall-customer-EDA
📊 Machine Learning Clustering Model - Unsupervised Learning

This project contains a Jupyter Notebook (`clustering.ipynb`) that demonstrates the application of clustering algorithms on two different datasets: Mall Customer Data and Live Social Media Data. 🚀

## 📝 Table of Contents
- [Project Overview](#project-overview)
- [Datasets Used](#datasets-used)
- [Models Used](#models-used)
- [Analysis and Results](#analysis-and-results)

## 🌟 Project Overview

This project aims to perform unsupervised learning using clustering techniques to identify natural groupings within the datasets. Specifically, the **K-Means algorithm** is utilized to segment customer data and analyze social media post interactions. 💡

## 💾 Datasets Used

1.  **Mall_Customers.csv**: This dataset contains customer information including CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100). It is used for customer segmentation based on annual income and spending score. 🛍️

2.  **Live.csv**: This dataset appears to contain social media post data, including various metrics like reactions, comments, shares, likes, loves, wows, hahas, sads, and angry reactions. It is used for analyzing patterns in social media engagement. 📱

## 🧠 Models Used

**K-Means Clustering**: This is the primary unsupervised machine learning algorithm used in this notebook. K-Means aims to partition `n` observations into `k` clusters in which each observation belongs to the cluster with the nearest mean (cluster centroids), serving as a prototype of the cluster. 🎯

-   **Elbow Method**: The Within-Cluster Sum of Squares (WCSS) is calculated for a range of cluster numbers (1 to 10) to determine the optimal number of clusters for the K-Means algorithm. This is visualized using a plot to identify the 'elbow' point. 📈

## 📊 Analysis and Results

### 🛍️ Mall Customer Data Analysis

-   **Feature Selection**: The 'Annual Income (k$)' and 'Spending Score (1-100)' columns are selected as features for clustering. 💰
-   **Optimal Clusters**: The Elbow Method is applied to find the optimal number of clusters, which is determined to be **5**. ✨
-   **Clustering**: K-Means is applied with 5 clusters to segment the mall customers. The clusters are visualized, showing distinct groups based on their income and spending habits. 👥

### 📱 Live Social Media Data Analysis

-   **Data Exploration**: The notebook explores the columns and value counts of 'status_type' in the `Live.csv` dataset. 🔍
-   **Feature Selection**: Features related to reactions (`num_reactions`, `num_comments`, `num_shares`, `num_likes`, `num_loves`, `num_wows`, `num_hahas`, `num_sads`, `num_angrys`) are selected for clustering. 👍
-   **Optimal Clusters**: The Elbow Method is applied, and the optimal number of clusters is determined to be **3**. 🌟
-   **Clustering**: K-Means is applied with 3 clusters to group social media posts based on their engagement metrics. The clusters are visualized. 💬




