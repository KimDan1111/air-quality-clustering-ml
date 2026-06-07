# Air Quality Clustering Analysis using Machine Learning

## Overview
This project applies unsupervised machine learning techniques to analyze global air quality data and uncover hidden environmental patterns. Multiple clustering algorithms are implemented and compared to evaluate their effectiveness in identifying pollution structures. The project includes data preprocessing, outlier handling, feature scaling, dimensionality reduction, clustering, and visualization.

## Objectives
- Clean and preprocess air quality dataset  
- Handle missing values and remove outliers  
- Standardize features for clustering  
- Reduce dimensionality using PCA  
- Apply multiple clustering algorithms: K-Means, Agglomerative (Hierarchical), OPTICS  
- Evaluate clustering performance using Silhouette Score and Davies-Bouldin Index  
- Visualize clusters in 2D space using PCA  

## Dataset
The dataset used in this project is sourced from Kaggle: Global Air Quality Dataset.  
It contains measurements of major air pollutants including PM2.5, PM10, NO2, and SO2.

## Machine Learning Techniques Used
- K-Means Clustering  
- Agglomerative Hierarchical Clustering  
- OPTICS (Density-Based Clustering)  
- PCA (Principal Component Analysis for visualization)  

## Evaluation Metrics
- Silhouette Score: Measures how well clusters are separated  
- Davies-Bouldin Index: Measures cluster compactness and separation  

## Key Insights
- Different clustering algorithms reveal different pollution patterns  
- OPTICS performs better for noisy and extreme pollution data  
- K-Means works well for structured datasets  
- Hierarchical clustering provides better interpretability of relationships  
- PCA enables clear visualization of high-dimensional air quality data  

## Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- SciPy  

## Project Structure
The project currently contains a Jupyter Notebook implementing all clustering workflows, along with dataset and results generated during analysis.


## Results
The clustering models successfully identified distinct air quality groups based on pollutant concentrations, revealing meaningful environmental patterns and pollution levels.

## Author
Esha Sajid

## Note
This project is for educational and portfolio purposes. The dataset is publicly available on Kaggle.
