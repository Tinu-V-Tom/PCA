# PCA
Principal Component Analysis (PCA) on the Breast Cancer Dataset
Introduction to PCA
Principal Component Analysis (PCA) is a dimensionality reduction technique used to transform a high-dimensional dataset into a lower-dimensional one while retaining as much variance as possible. It achieves this by finding new axes (principal components) that maximize the variance of the data. The first principal component accounts for the most variance, and each subsequent component captures the remaining variance orthogonal to the previous components.

Why Use PCA?
Reduce computational complexity.
Remove multicollinearity by creating uncorrelated features.
Facilitate visualization in 2D or 3D for high-dimensional datasets.
Help in noise reduction and data compression.
Dataset: Breast Cancer Dataset

Applying PCA to Reduce Dimensions to 2
Data Preprocessing:

Load the dataset.
Standardize the data using z-score normalization (zero mean and unit variance). This is important because PCA is sensitive to the scale of features.
Dimensionality Reduction with PCA

