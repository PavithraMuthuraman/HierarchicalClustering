# Hierarchical Clustering
*Hierarchical Clustering Analysis on Multiple Datasets*

**Description**: This project employs hierarchical clustering to analyze and group data from three different datasets: Diabetes, Country Clusters, and Wholesale Customers. Dendrograms are used to visualize the clustering process, providing insights into the structure of the data.

## Project Overview
- **Objective**: Use hierarchical clustering to identify patterns and group similar data points within each dataset.
- **Model**: Hierarchical clustering with the Ward method is applied to create dendrograms for visualizing the clusters.
- **Datasets**:
  1. **Diabetes Dataset**: Contains health-related data, excluding the 'Outcome' column, used to identify clusters of similar health profiles.
  2. **Country Clusters Dataset**: Groups countries based on their geographical coordinates (latitude and longitude) and primary language spoken.
  3. **Wholesale Customers Dataset**: Analyzes purchasing behavior to cluster customers with similar buying patterns.

## Files Included
- **diabetes.csv**: The dataset used for clustering health profiles.
- **Country_clusters.csv**: The dataset used for clustering countries.
- **Wholesale_customers_data.csv**: The dataset used for clustering wholesale customers.
- **HierarchicalClustering.ipynb**: The Python notebook that performs data preprocessing, model training, and clustering.

## Code Execution 
1. **Setup Environment**: Install the required libraries (`numpy`, `pandas`, `scipy`, `matplotlib`).
2. **Data Loading**: Load each dataset from the appropriate directory and inspect the data.
3. **Preprocessing**: Select the relevant features for clustering from each dataset.
4. **Model Training**: Apply hierarchical clustering to the selected features using the Ward method to generate dendrograms for each dataset.
5. **Clustering**: Analyze the dendrograms to interpret the clusters and understand the data groupings across different contexts.

