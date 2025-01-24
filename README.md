# AirQ-SVD
Simplifying Air Quality Data with Clustering and SVD

## Overview
This project analyzes air quality patterns using the UCI Air Quality dataset. It employs machine learning techniques such as clustering, dimensionality reduction, and predictive modeling to uncover insights into pollution levels and improve data analysis efficiency.

## Objectives
- Identify air quality patterns using K-Means clustering.
- Simplify the dataset with Randomized Singular Value Decomposition (SVD).
- Build predictive models to forecast pollution levels.

## Dataset
[UCI Air Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Air+Quality)

## Tools & Technologies
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib.
- **Machine Learning**: K-Means Clustering, Randomized SVD, Linear Regression.
  
## Key Features

### 1. Data Cleaning
- Removed noisy and redundant data.
- Handled missing values and normalized features.

### 2. Exploratory Data Analysis (EDA)
- Discovered correlations between pollutants and environmental factors.
- Analyzed temporal and seasonal trends in pollution data.

### 3. Clustering
- Grouped data into low, moderate, and high pollution levels using K-Means.
- Validated results using the Elbow Method and Silhouette Score.

### 4. Dimensionality Reduction
- Reduced dataset complexity from 5 to 3 components using Randomized SVD.
- Achieved a reconstruction error of approximately 0.39 while retaining over 60% variance.

### 5. Predictive Modeling
- Built Linear Regression models before and after SVD.
- Improved computational efficiency with minimal loss in accuracy.

## Results
- Effective clustering of pollution levels.
- Reduced dimensionality with acceptable information loss.
- Regression models post-SVD achieved RMSE of 0.2183 and R² of 0.9747.

