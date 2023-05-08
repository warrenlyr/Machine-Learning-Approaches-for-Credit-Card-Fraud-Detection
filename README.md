# Machine Learning Approaches for Credit Card Fraud Detection

This project signifies the culmination of my work for the CSS581: Machine Learning course. The focus of the project was to employ an array of supervised and unsupervised machine learning models for the detection of credit card fraud. For an in-depth look at the implementations and findings, please refer to the `Report` folder. The `data` folder houses the dataset used in the project, while the `output` folder contains a collection of images derived from the project. The core source code can be found in the `src` folder.

Term: Winter 2023

Author: Warren Liu

## Modeling Approach

### Supervised Learning

For the supervised learning segment of the project, I utilized classification models, specifically:

- K-Nearest Neighbors (KNN)
  - Standard model with unbalanced data
  - Model with undersampling
  - Model with oversampling
- Decision Tree
  - Standard model with unbalanced data
  - Model with undersampling
  - Model with oversampling
- Balanced Random Forest

### Unsupervised Learning

In the realm of unsupervised learning, I employed outlier detection models, which included:

- Hierarchical Density-Based Spatial Clustering of Applications with Noise (HDBSCAN)
  - Standard model
  - Model with a manually set threshold
- Principal Component Analysis (PCA)
- Local Outlier Factor (LOF)
- Autoencoder Neural Network (ANN)