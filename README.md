# ML-Assignment-5-Clustering-Algorithm
Iris Dataset Clustering

This project implements KMeans Clustering and Hierarchical Clustering on the Iris dataset from the scikit-learn library. The goal is to group similar data points without using class labels and visualize the resulting clusters.

📊 Project Overview

Dataset: Iris dataset (150 samples, 4 features)

Clustering Algorithms:

KMeans Clustering

Hierarchical Clustering

1. Data Loading & Preprocessing

Load the Iris dataset from sklearn.datasets.

Drop the target column (species) for unsupervised clustering.

Standardize the features using StandardScaler for better clustering performance.

2. KMeans Clustering

Algorithm: Partition-based, iterative clustering algorithm.

Why KMeans?: Efficient and suitable since the Iris dataset naturally divides into three species.

Visualization: Scatter plot of the first two features with KMeans clusters.

3. Hierarchical Clustering

Algorithm: Builds a dendrogram by merging clusters.

Why Hierarchical?: No need to predefine the number of clusters and provides a detailed cluster hierarchy.

Visualization: Dendrogram to show cluster merging.
