K-Means Clustering on Mall Customers Dataset-

1) Imported and cleaned the dataset by dropping irrelevant columns (CustomerID, Gender) and handling outliers using the Z-score method.
   
2) Visualized feature distributions using boxplots before and after outlier removal.

3) Scaled the numerical features using StandardScaler to ensure balanced clustering.

4) Applied PCA to reduce dimensionality to 2D for intuitive visualization of customer segments.

5) Trained K-Means models with different values of K and visualized clusters in 2D PCA space.

6) Used the Elbow Method to identify the optimal number of clusters based on inertia.

7) Evaluated clustering performance using the Silhouette Score to assess the quality of cluster separation.
