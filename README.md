# Elevate-Labs-Task-8
# Mall Customer Segmentation using K-Means Clustering

This task performs customer segmentation on the Mall Customer dataset using K-Means clustering. The goal is to identify distinct customer groups based on their annual income and spending score.

## Dataset

The dataset `Mall_Customers.csv` contains the following features:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

## Steps Performed

1. **Data Exploration and Visualization**
   - Checked dataset info, summary statistics, and missing values.
   - Visualized distributions and boxplots for numerical features.
   - Created pairplots and gender-wise comparisons.
   - Plotted correlation heatmap.

2. **Feature Selection and Scaling**
   - Selected `Annual Income` and `Spending Score` for clustering.
   - Applied standard scaling to normalize features.

3. **Dimensionality Reduction**
   - Used PCA for 2D visualization of customer distribution.

4. **Optimal Cluster Selection**
   - Applied the Elbow Method to determine the optimal number of clusters (`k=5`).

5. **K-Means Clustering**
   - Fitted the K-Means algorithm with `k=5`.
   - Assigned cluster labels and visualized the segmented clusters.

6. **Evaluation**
   - Computed the **Silhouette Score** to assess cluster quality.
   - **Silhouette Score for K=5**: `0.555`, indicating reasonably well-separated clusters.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
