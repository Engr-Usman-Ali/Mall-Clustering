# Mall Customers Clustering — KMeans (Unsupervised Learning)
This project applies K-Means clustering to the Mall Customers Dataset to segment customers into distinct groups based on their Annual Income and Spending Score. It’s part of a data science internship task focused on unsupervised learning techniques.

# Objective
To group customers into meaningful clusters using K-Means Clustering and visualize these segments for business insights.

# 📊 Dataset
Filename: Mall_Customers.csv

# 📈 Visualizations
# Elbow Method — Optimal Number of Clusters (k)
The Elbow Method was used to determine the optimal number of clusters. The Within-Cluster Sum of Squares (WCSS) is plotted against various values of k to identify the "elbow point" — the value after which WCSS decreases more slowly.

**📊 Result:**
The elbow clearly appeared at k = 5 clusters.

![alt img](https://github.com/Engr-Usman-Ali/Mall-Clustering/blob/8890a9611388e28e62afe62de005111547278e91/1.png)

# Cluster Visualization (Scatter Plot)
Once the clusters were formed using k=5, a scatter plot was generated using the two selected features. Customers are colored according to their assigned cluster, providing a clear visual separation between groups.

Cluster Scatter Plot Example:

![alt img](https://github.com/Engr-Usman-Ali/Mall-Clustering/blob/8890a9611388e28e62afe62de005111547278e91/2.png)

# 📊 Results & Interpretation
Each cluster represents a customer segment:
+ Cluster 0: Moderate Income — Low Spending
+ Cluster 1: High Income — High Spending
+ Cluster 2: Low Income — Low Spending
+ Cluster 3: Moderate Income — High Spending
+ Cluster 4: High Income — Low Spending

These segments help businesses target customers with personalized offers and marketing strategies.


# What to Focus On
**How the number of clusters was chosen:**
The Elbow Method was applied by plotting the WCSS for cluster counts ranging from 1 to 10. The point where the curve starts to flatten (the "elbow") indicates an appropriate number of clusters — in this case, 5.

**Clear visualization of the clusters:**
The scatter plot uses different colors for each cluster, showing how customers are grouped based on Annual Income and Spending Score.

