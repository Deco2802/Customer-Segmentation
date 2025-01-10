Customer Segmentation Using K-Means Clustering
This project performs customer segmentation using the K-Means clustering algorithm. The segmentation is based on demographic and behavioral features of customers, such as age, gender, annual income, and spending score. The goal is to group customers into clusters to better understand their purchasing behavior and target them effectively.

Dataset
The dataset used for this project is the Mall Customers Dataset. It contains information about customers' demographics and shopping behavior. Key features include:

Genre: Gender of the customer (Male/Female)
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousands of dollars
Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature
Preprocessing Steps
Removed unnecessary columns (e.g., CustomerID).
Encoded categorical features using Label Encoding and One-Hot Encoding.
Created additional features like Income Range, Age Group, and Spending Score Range using binning.
Scaled features using MinMaxScaler for better clustering performance.
Methodology
Clustering
Used the K-Means algorithm to group customers into distinct clusters.
Determined the optimal number of clusters using:
Elbow Method (WCSS curve).
Silhouette Score.
Davies-Bouldin Index for additional validation.
Dimensionality Reduction
Applied Principal Component Analysis (PCA) to visualize clusters in:
2D scatter plot.
3D scatter plot.
Visualizations
Generated visualizations to understand cluster distribution and characteristics:
Elbow Curve for WCSS.
Silhouette Score vs. Number of Clusters.
2D and 3D scatter plots for cluster visualization.
Results
Customers were segmented into 5 clusters based on behavioral and demographic features.
Each cluster represents a specific customer segment, helping businesses tailor marketing strategies.
