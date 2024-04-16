# Unsupervised Clustering Analysis

This repository contains a Jupyter notebook that explores unsupervised machine learning techniques to determine the best clustering algorithm for a given dataset. We evaluate four different algorithms: K-Means, Agglomerative Clustering, MeanShift, and DBSCAN, each optimized for maximum performance using various parameter tuning strategies.

## Overview

The goal of this analysis is to identify the most effective clustering algorithm for our dataset based on silhouette scores. We aim to demonstrate which algorithm most effectively partitions the data into distinct and coherent clusters.

### Algorithms Evaluated

- **K-Means Clustering**: Optimized through grid search with parameters like number of clusters and number of initializations.
- **Agglomerative Clustering**: Tuned using a randomized search covering different linkage methods and affinity metrics.
- **MeanShift**: Parameters such as bandwidth are optimized using grid search informed by the `estimate_bandwidth` function.
- **DBSCAN**: Explores a range of eps values and minimum samples through grid search to find optimal settings.

## Files in the Repository

Unsupervised_Clustering_Analysis.ipynb: The Jupyter notebook containing all the code and analysis.
README.md: This file, providing an overview and instructions for running the notebook.

## Results

The analysis revealed that Agglomerative Clustering yielded the best performance with the highest silhouette score, suggesting it was most effective at distinguishing clusters within the dataset. The notebook contains a detailed comparison and visualization of results from all the algorithms tested.

## Prerequisites

Before running the notebook, ensure you have the following requirements installed:

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

You can install all required libraries using the following command:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn

