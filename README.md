# Clustering Methods and Evaluation Scores

This README provides an overview of four popular clustering methods and explains the evaluation metrics used to assess their performance.

## Clustering Methods

### 1. KMeans Clustering
KMeans is a centroid-based clustering algorithm that partitions data into K clusters. It aims to minimize the variance within clusters by iteratively assigning data points to the nearest cluster center.

### 2. DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
DBSCAN is a density-based clustering algorithm that identifies clusters based on regions of high density separated by areas of low density. It doesn't require specifying the number of clusters beforehand and can identify outliers as noise.

### 3. Gaussian Mixture Model (GMM)
GMM assumes that the data is generated from a mixture of several Gaussian distributions. It estimates the parameters of these distributions to assign probabilities of data points belonging to each cluster, accommodating clusters with different shapes and sizes.

### 4. Agglomerative Clustering
Agglomerative clustering is a hierarchical clustering method that starts with each data point as a single cluster and iteratively merges the closest clusters based on a chosen linkage criterion (e.g., Ward, complete, average) until all points belong to a single cluster.

## Evaluation Metrics

### 1. Silhouette Score
The silhouette score measures the cohesion and separation of clusters. It quantifies how similar an object is to its own cluster compared to other clusters, ranging from -1 (incorrect clustering) to +1 (highly dense clustering).

### 2. Calinski-Harabasz Index
The Calinski-Harabasz index is a ratio of the sum of between-clusters dispersion and within-cluster dispersion. Higher values indicate better-defined clusters.

### 3. Davies-Bouldin Index
The Davies-Bouldin index measures the average similarity between each cluster and its most similar cluster. Lower values indicate better clustering.

### 4. Adjusted Rand Index (ARI)
The adjusted Rand index assesses the similarity between the predicted clustering and the ground truth labels (if available). It ranges from -1 to 1, where 1 indicates perfect clustering agreement with the ground truth labels.

# Clustering Evaluation Scores

| Metric                     | KMeans     | Gaussian Mixture Model | Agglomerative Clustering  |
|----------------------------|------------|------------------------|---------------------------|
| Silhouette Score           | 0.7916     | 0.7916                 | 0.7916                    |
| Calinski-Harabasz Index    | 11066.9713 | 11066.9713             | 11066.9713                |
| Davies-Bouldin Index       | 0.2923     | 0.2923                 | 0.2923                    |
| Adjusted Rand Index        | -0.0007    | -0.0007                | -0.0007                   |
