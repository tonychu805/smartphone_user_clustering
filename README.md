# Smartphone User Clustering

## Summary

Introduction: This is a project from my master's degree. It aims to explore and analyze data on smartphone users, apply various data preprocessing techniques, and implement multiple clustering algorithms.
  
Exploratory Data Analysis (EDA): The initial steps involve loading the dataset, examining its structure, and conducting descriptive statistics. Visualizations like histograms and box plots are used to understand data distributions and relationships.

Data Preprocessing: This section covers handling missing values, creating dummy variables for categorical data, and examining outliers. Various transformations are applied to prepare the data for modeling, including mean/media/mode imputation, forward/backward fill, and KNN imputation.

Clustering Analysis: The notebook explores different clustering techniques such as k-means, hierarchical clustering, DBSCAN, and soft clustering using the Fanny method. It includes detailed steps for model training, tuning, and evaluation using visualizations like dendrograms, silhouette plots, and cluster plots.

Model Evaluation: Performance of clustering models is assessed using appropriate metrics and visualizations. The results are compared to draw insights and conclusions about the data patterns and clusters.

Results: There seems to be naturally occurred clusters when using K-means partition clustering method with k value of 3 (optimal number of cluster). This configuration seems to be optimal for classifying the smartphone user dataset crisply.

## Git Repository content

- Data Mining - Graded Assignment.ipynb to record the analysis
- Data Mining - Graded Assignment.xlsx is the raw data.

## Dependencies and libraries

The notebook utilizes a variety of R libraries, which are essential for data manipulation, visualization, and modeling:

- dplyr
- magrittr
- ggplot2
- tidyverse
- finalfit
- Hmisc
- pastecs
- psych
- corrplot
- DiscriMiner
- base
- reshape2
- resample
- dendextend
- fpc	
- dbscan
- cluster
