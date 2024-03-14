# Respiratory Disease Clustering using Machine Learning

This repository contains Python code for clustering respiratory disease data using various machine learning algorithms and techniques. The main steps include:

## Data Loading and Preprocessing:
- Download the Dataset_all.xlsx file to DataFrame.
- Custom method for filling gaps in the dataset using fuzzy spatial extrapolation.
- Excluding columns with more than 20% missing values.
- Normalizing or standardizing features for model compatibility.
- Visualizing DataFrame using Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE) methods.

## Clustering and Evaluation:
- Use of different clustering approaches such as Affinity Propagation, Agglomerative Clustering, DBSCAN, Feature Agglomeration, KMeans, Spectral Clustering, Spectral Biclustering, and Spectral Coclustering.
- Tuning parameters for each clustering algorithm.
- Comparison of clustering results with the Diagnosis column using metrics such as Adjusted Rand Index (ARI), Adjusted Mutual Information (AMI), Homogeneity, Completeness, and V-measure.
- Selection of the best clustering algorithm based on performance metrics.

## Feature Selection and Improvement:
- Feature selection preprocessing stage using methods like Variance Threshold to improve clustering results.
- Reevaluation of clustering algorithms after feature selection to determine the best performing algorithm.

## Repository Structure:
- **README.md**: Contains information about the project, dataset, methods, and results.
- **Dataset_all.xlsx**: Excel file containing the respiratory disease dataset.
- **respiratory-disease-ml-clustering.ipynb**: Jupyter notebook containing Python code for data processing, clustering, evaluation, and improvement.

## Instructions for Running the Code:
1. Ensure you have Python installed on your system along with the necessary libraries specified in the notebook.
2. Download the dataset (Dataset_all.xlsx) and place it in the root directory.
3. Open and run the respiratory-disease-ml-clustering.ipynb notebook using Jupyter or any compatible environment.
4. Follow the instructions and execute the code cells sequentially to perform data processing, clustering, evaluation, and improvement.

## Results Summary:
- The project employs various machine learning clustering algorithms, including Affinity Propagation, Agglomerative Clustering, DBSCAN, KMeans, Spectral Clustering, Spectral Biclustering, and Spectral Coclustring, to analyze respiratory disease data. 
- Extensive parameter tuning is conducted to optimize the performance of each clustering algorithm, with a focus on metrics such as Adjusted Rand Index (ARI), Adjusted Mutual Information (AMI), Homogeneity, Completeness, and V-measure. 
- Additionally, a feature selection preprocessing stage is introduced to enhance clustering outcomes, ultimately identifying the SpectralCoclustering algorithm as the most effective solution for grouping respiratory disease data.

Clustering techniques for respiratory disease data offer invaluable insights into disease patterns, facilitating more accurate diagnoses, personalized treatment plans, and ultimately, improved patient outcomes.
