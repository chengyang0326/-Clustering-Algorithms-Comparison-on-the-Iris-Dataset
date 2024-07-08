# Clustering Algorithms Comparison on the Iris Dataset

## Overview

This repository contains a Jupyter Notebook (`clustering_algorithms_comparison.ipynb`) that explores three popular clustering algorithms—KMeans, Agglomerative Clustering, and DBSCAN—applied to the Iris dataset. Each algorithm is evaluated based on its clustering performance using the Silhouette Score and visually represented through scatter plots.

## Usage

1. **Download the Notebook**

2. **Open the Notebook**: Navigate to the Jupyter Notebook file (`clustering_algorithms_comparison.ipynb`) on GitHub and click on it to view the contents.

3. **Run the Cells**: Open the notebook in a Jupyter environment (e.g., Google Colab or local Jupyter Notebook), and execute each cell sequentially to run the code and observe the results.

## Clustering Algorithms

### 1. KMeans Clustering

KMeans is a centroid-based clustering algorithm that partitions the dataset into k clusters, minimizing the variance within each cluster.

- **Parameters**: Number of clusters (`n_clusters`).
- **Evaluation**: Silhouette Score for clustering quality.

### 2. Agglomerative Clustering

Agglomerative Clustering is a hierarchical clustering method that builds clusters from the bottom-up, merging clusters based on distance metrics.

- **Parameters**: Number of clusters (`n_clusters`).
- **Evaluation**: Silhouette Score for clustering quality.

### 3. DBSCAN Clustering

DBSCAN identifies clusters based on density, suitable for datasets with noise and varying cluster shapes.

- **Parameters**: `eps` (distance threshold) and `min_samples` (minimum number of points in a neighborhood).
- **Evaluation**: Silhouette Score for clustering quality.

## Outputs

Each section in the notebook includes:

- **Silhouette Score**: A measure of clustering quality.
- **Visualization**: Scatter plot showing the clustered data points.

## Conclusion

This project demonstrates the application of different clustering algorithms on the Iris dataset. The choice of algorithm depends on the dataset characteristics and desired cluster properties.
