# Clustering News Articles or Blog Posts

## Description

This Python code demonstrates the process of clustering news articles or blog posts into distinct groups using two different clustering techniques: Hierarchical Clustering and K-Means Clustering. The dataset used contains articles with multiple features, and the goal is to group similar articles together based on their content.

## Code Highlights

1. **Data Loading and Preprocessing:** The code starts by reading a CSV file ('dailykos.csv') containing the article data and performs data preprocessing by dropping rows with missing values.

2. **Hierarchical Clustering:**
   - Computes Euclidean distances between all pairs of articles.
   - Converts the distances into a square matrix.
   - Generates a linkage matrix using the Ward method.
   - Plots a dendrogram to visualize the hierarchical clustering.
   - Assigns cluster labels based on a specified threshold.

3. **K-Means Clustering:**
   - Performs K-Means clustering with a specified number of clusters (in this case, 7 clusters).
   - Assigns cluster labels to the articles.
   - Identifies the cluster with the most and least number of observations.
   - Prints the top words that occur most frequently in each cluster.

4. **Comparison and Contingency Table:**
   - Compares the clustering results obtained from Hierarchical Clustering and K-Means Clustering.
   - Creates a contingency table to visualize the overlap between the two clustering methods.

## Usage and Interpretation

- The code allows users to explore and cluster a dataset of news articles or blog posts.
- Users can adjust the number of clusters and criteria for clustering according to their specific needs.
- It provides insights into which clusters may correspond to particular topics or themes within the dataset.

## Dependencies

- Python 3.x
- Libraries: pandas, scipy, matplotlib, and scikit-learn

## Author

Ravi Teja Thandra

## Acknowledgments

- 'dailykos.csv' Data set
