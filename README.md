# Dimensionality Reduction and Clustering

## Objectives
- Introduce dimensionality reduction through PCA.
- Introduce Clustering through K-means.
- Implement PCA and K-Means correctly.
- Evaluate the impact of dimensionality reduction on clustering results.

## Problem Statement
Given the Breast Cancer Wisconsin (Diagnostic) dataset, the objective is to perform unsupervised clustering to identify inherent patterns or groupings within the dataset. This dataset contains features computed from digitized images of fine needle aspirates (FNAs) of breast masses, aiming to distinguish between malignant and benign tumors.

## Assignment Details and Requirements
1. Implement K-Means using NumPy.
2. Implement PCA using NumPy.
3. Conduct two experiments:
    - First experiment: Cluster the dataset using k-means.
    - Second experiment: Apply PCA then cluster the dataset using k-means.
4. In both experiments:
    - Apply the elbow method to find the best number (local minimum) of k clusters.
    - Compare the sum of square errors/distances in both experiments.
    - Add notes in both experiments.
5. In the second experiment:
    - Experiment with different numbers of principal components.
    - Visualize the results and compare them with the original labels.

## Experiment 1: K-Means Clustering without PCA
- Implement K-Means algorithm using NumPy.
- Apply the elbow method to find the optimal number of clusters.
- Cluster the dataset without using PCA.
- Compare the clustering results with the original labels.
- Add notes on observations and insights gained.

## Experiment 2: PCA followed by K-Means Clustering
- Implement PCA using NumPy.
- Experiment with different numbers of principal components.
- Apply K-Means clustering after PCA dimensionality reduction.
- Apply the elbow method to find the optimal number of clusters.
- Visualize the results and compare them with the original labels.
- Compare the sum of square errors/distances with Experiment 1.
- Add notes on observations and insights gained, especially focusing on the impact of dimensionality reduction on clustering.
