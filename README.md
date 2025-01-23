# clustering

# Clustering Algorithms on Iris Dataset


## Dataset
The dataset used is the Iris dataset available in the `sklearn` library.

## Key Components

### 1. Loading and Preprocessing
- Load the Iris dataset from `sklearn`.
- Drop the species column since this is a clustering problem.

### 2. Clustering Algorithm Implementation 

#### A) KMeans Clustering
- **Description of KMeans Clustering**: 
  KMeans is a centroid-based clustering algorithm. It partitions data into 'K' clusters, where each cluster is represented by its centroid. The algorithm minimizes the variance within clusters, iteratively adjusting centroids until convergence.
  
- **Suitability for the Iris dataset**: 
  The Iris dataset is suitable for KMeans clustering because it has continuous numeric features and known separable groups (species), making it a good candidate for centroid-based partitioning.

- **Implementation**:
  Applied KMeans clustering to the preprocessed Iris dataset and visualized the clusters using PCA and t-SNE.

#### B) Hierarchical Clustering
- **Description of Hierarchical Clustering**: 
  Hierarchical clustering builds a tree (dendrogram) representing nested clusters. The algorithm can be divisive (top-down) or agglomerative (bottom-up). The clusters are formed by grouping data points based on their similarity.
  
- **Suitability for the Iris dataset**: 
  Hierarchical clustering is suitable for the Iris dataset because it provides a detailed view of how data points cluster at different levels, which can reveal relationships between clusters.

- **Implementation**:
  Applied Hierarchical clustering to the preprocessed Iris dataset and visualized the clusters using PCA and t-SNE.



## Visualizations
The notebook includes visualizations of the clusters using PCA and t-SNE for both KMeans and Hierarchical clustering algorithms.

## Evaluation Metrics
- **Silhouette Score**: Evaluates how similar an object is to its own cluster compared to other clusters.
- **Davies-Bouldin Score**: Measures the average similarity ratio of each cluster with its most similar cluster.


