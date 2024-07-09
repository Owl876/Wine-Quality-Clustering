# Wine Quality Clustering
Multilevel cluster analysis of wine quality characteristics based on chemical composition.

This repository contains a comprehensive implementation of a project aimed at clustering wine samples based on various chemical properties to predict quality levels.

## Dataset

The dataset used in this project is the Wine Quality dataset, which can be found on the UCI Machine Learning Repository - https://archive.ics.uci.edu/dataset/186/wine+quality.

## Attributes:

- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality (target variable)

## Project Overview

This project focuses on clustering the wine samples to understand the distribution of wine quality based on their chemical properties. The clustering helps in identifying key features that influence wine quality and grouping similar wine samples together.
Steps Included:

1. Data Preprocessing:
   - Standardized the data to normalize the feature values.
   - Applied Principal Component Analysis (PCA) to reduce dimensionality and visualize the data.

2. Clustering:
   - Implemented K-means clustering with different cluster sizes (4, 5, and 6) to identify optimal clusters.
   - Implemented DBSCAN clustering for density-based clustering.
   - Analyzed cluster characteristics to determine the quality levels.

3. Dimensionality Reduction:
   - Applied t-SNE for advanced dimensionality reduction and visualization of high-dimensional data.

4. Visualization:
   - Created boxplots for each feature by cluster to visualize the distribution and key characteristics.
   - Plotted the clusters using PCA and t-SNE components to observe the grouping of wine samples.

5. Cluster Analysis:
   - Analyzed the mean values of each cluster to interpret the key features and quality levels.
   - Evaluated the distribution of chemical properties across clusters to understand the impact on quality.
