# Wine Dataset Clustering Analysis

## Overview

This repository contains a clustering analysis performed on the Wine dataset using two popular clustering techniques: **K-Means Clustering** and **Hierarchical Clustering**. The goal is to explore the structure of the dataset, identify the optimal number of clusters, and compare the effectiveness of both clustering methods.

## Introduction

Clustering is a powerful unsupervised machine learning technique used to group similar data points together. In this project, we apply K-Means and Hierarchical Clustering to the Wine dataset, which is included in the scikit-learn library. The analysis includes determining the optimal number of clusters using the Elbow Method for K-Means and a dendrogram for Hierarchical Clustering.

## Dataset

The Wine dataset contains 13 features, including alcohol content, malic acid, ash, and more. It is a well-known dataset in the machine learning community, commonly used for classification and clustering tasks.

## Clustering Techniques

### K-Means Clustering

- **Elbow Method:** We use the Elbow Method to determine the optimal number of clusters by plotting the Within-Cluster Sum of Squares (WSS) against the number of clusters.
- **Cluster Assignment:** After determining the optimal number of clusters, we assign data points to clusters and visualize the results.

### Hierarchical Clustering

- **Dendrogram:** A dendrogram is plotted to visually assess the clustering process and identify the optimal number of clusters.
- **Agglomerative Clustering:** We apply Agglomerative Clustering with the Ward linkage method to cluster the data points.

## Visualizations

- **Elbow Plot:** Used to identify the optimal number of clusters in K-Means.
- **Dendrogram:** Visual representation of the clustering hierarchy in Hierarchical Clustering.
- **Scatter Plots:** Visualize the clusters formed by both K-Means and Hierarchical Clustering.

## Conclusion

The analysis concludes that while both K-Means and Hierarchical Clustering are effective, Hierarchical Clustering provided a slightly better representation of the data structure in this particular case. This conclusion is based on the visual assessment and the natural grouping of data points observed in the dendrogram.
