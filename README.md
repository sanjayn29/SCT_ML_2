# SCT_ML_2
# K-means Clustering on Mall Customer Dataset

This project applies **K-means clustering** to group customers of a retail store based on their purchase history. It uses the **Mall Customer Dataset** and determines optimal clusters using the **Elbow Method**.

## Task Description
This is **Task 02** of my project at **Skillcraft Technology**.

### Goal:
- Group customers into clusters based on **Annual Income** and **Spending Score**.
- Identify patterns and insights from the clusters.

## Files Included
- **Mall_Customers.csv**: The dataset used for clustering.
- **Mall_Customers_with_Clusters.csv**: The output file containing cluster labels for each customer.
- **kmeans_clustering_mall.py**: Python script to implement the clustering algorithm.

## Steps Performed
1. **Data Preprocessing**
   - Load the dataset and inspect the data.
2. **Optimal Clusters using Elbow Method**
   - Analyze inertia values for different cluster counts.
3. **K-means Clustering**
   - Apply the algorithm to group customers.
4. **Visualization**
   - Plot the results to visualize customer segments.

## Requirements
- Python 3
- Libraries: Pandas, Matplotlib, Scikit-learn

## Running the Code
```bash
python kmeans_clustering_mall.py
```

## Output
- The clustered dataset is saved as **Mall_Customers_with_Clusters.csv**.
- Plots show the **Elbow Method** and **Cluster Visualization**.

## Author
- **Sanjay N** - Skillcraft Technology

## License
This project is licensed under the MIT License.
