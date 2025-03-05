# PCA-clustering-analysis

# Overview
This project explores Principal Component Analysis (PCA) for dimensionality reduction and its impact on clustering performance.
The analysis includes:

* Exploratory Data Analysis (EDA)
 Dimensionality Reduction with PCA
 Clustering on Original vs. PCA-Transformed Data
 Performance Evaluation and Comparison
 Insights on the Trade-offs of PCA in Clustering
# Project Workflow
1. Exploratory Data Analysis (EDA)
* Load the dataset and perform initial analysis
* Visualize feature distributions using histograms, box plots, and density plots
* Identify correlations between features
2. Dimensionality Reduction with PCA
* Standardize the dataset (zero mean, unit variance)
* Apply PCA to reduce dimensionality
* Determine the optimal number of principal components using scree plot and cumulative explained variance.
* Transform the dataset into principal components
3. Clustering on Original Data
* Apply K-Means Clustering (or another algorithm) on the original dataset
* Visualize the clustering results
* Evaluate clustering performance using Silhouette Score and Davies–Bouldin Index
4. Clustering on PCA-Transformed Data
* Apply the same clustering algorithm on PCA-transformed data
* Visualize clustering results after dimensionality reduction
* Compare performance with original dataset clustering
5. Comparison and Analysis
* Compare clustering results from original vs. PCA-transformed data
* Discuss the impact of dimensionality reduction on clustering performance
* Evaluate trade-offs between clustering directly on raw data vs. reduced data
6. Conclusion and Insights
* Summarize key findings and observations
* Discuss practical implications of using PCA in clustering
* Provide recommendations on when to use PCA vs. original feature space

# Key Learnings
* Understanding PCA for dimensionality reduction
* How PCA affects clustering results
* The importance of feature scaling before PCA
* Evaluating clustering performance on transformed data
