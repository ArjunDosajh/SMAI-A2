# SMAI Assignment 2 README

This README provides an overview of the completed tasks for the Statistical Methods in Artificial Intelligence (SMAI) Assignment 2.

## Problem 1: PCA

### PCA [25]
- Performed dimensionality reduction on IIIT-CFW dataset using PCA, varying the number of principal components
- Plotted the relationship between cumulative explained variance and number of principal components
- Performed dimensionality reduction on features from Assignment 1 (pictionary dataset), compared results and noted observations
- Observed impact of dimensionality reduction on dataset by using a classifier pre and post-reduction, varying principal components from 1 to n

### Pictionary Dataset [10]
- Performed PCA on Pictionary Dataset for both drawer and guesser
- Plotted features with respect to obtained PCA axes
- Analyzed what each new PCA axis represents

## Problem 2: GMM

### GMM: Gaussian Mixture Models [25]
- Implemented EM algorithm for GMM and performed clustering on customer-dataset, varying number of components
- Implemented GMM class with routines to fit data, obtain parameters, calculate likelihoods, and obtain membership values
- Performed clustering on wine-dataset using GMM and K-Means, found optimal number of clusters using BIC and AIC
- Reduced dataset dimension to 2 using PCA, plotted scatter plots, analyzed observations
- Computed silhouette scores for each clustering and compared results

## Problem 3: Hierarchical Clustering

### Hierarchical Clustering: Linkages and Features [25]
- Implemented Hierarchical clustering using classes and methods (hc.linkages, hc.dendogram)
- Performed hierarchical clustering on dataset, varied linkages and features, noted observations, plotted dendogram
- Performed hierarchical clustering on gene expression dataset, varied linkages and features, noted observations, plotted dendogram

## Problem 4

### Problem 4.1 [20]
- Aligned remaining shapes based on orientation of given template shape from KIMIA-99 dataset
- Wrote flowchart of algorithm used in Jupyter Notebook as markdown

### Problem 4.2 [20]
- Determined optimal horizontal and vertical Euclidean distance thresholds between bounding boxes containing words on document page
- Established connections between boxes within paragraph, ensured boxes across paragraphs and columns remain unconnected
- Modified and ran provided scripts for visualizing enclosing and connecting boxes

### Problem 4.3 [20]
- Found likely color components generating the provided 2D point dataset
- Created function to generate sample dataset with n likely components described by input parameters

The code for each problem can be found in separate Jupyter Notebooks, along with necessary observations in markdown format.
