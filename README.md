This project performs customer segmentation using unsupervised machine learning techniques on the Mall Customers dataset. The primary objective is to group customers into meaningful clusters based on their Annual Income and Spending Score, allowing businesses to understand different customer types and target them accordingly.

🔍 Key Steps in the Project:
Data Loading & Preprocessing

Loaded the Mall_Customers.csv dataset.

Dropped irrelevant columns like CustomerID.

Encoded the Genre (Gender) column to numeric values for optional use.

Feature Selection & Scaling

Selected Annual Income (k$) and Spending Score (1-100) for clustering.

Scaled the features using StandardScaler to normalize the data.

K-Means Clustering

Determined the optimal number of clusters (k) using the Elbow Method and Silhouette Score.

Applied K-Means clustering with the selected k value (typically 5).

Assigned each customer to a cluster and visualized the results using scatter plots.

Cluster Analysis

Calculated the average income and spending score for each cluster to understand customer segments.

Bonus: DBSCAN Clustering

Applied DBSCAN as an alternative clustering method to identify non-linear clusters and noise points.

🎯 Results:
The K-Means algorithm successfully segmented customers into distinct groups such as:

High income, high spenders

Low income, low spenders

Moderate income, moderate spenders, etc.

The analysis can help businesses improve targeted marketing, personalized offers, and customer retention strategies.
