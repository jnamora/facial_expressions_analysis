# Facial Expressions Analysis

## Overview

This project focuses on analyzing facial expressions from videos.


It was completed as part of the Master's in Engineering and Data Science program at the University of Coimbra (November, 2023).


###1 part
### Data Preprocessing


1. **Dataset Organization:**
   - For each subject, a dictionary is created, mapping emotions to the corresponding files using `listdir()` and `string.split()` functions.

2. **Data Loading:**
   - Using NumPy 3d array to store the data.
     

### Visualizations

1. **Expression Visualization:**
   - A function is implemented to visualize facial expressions based on landmark coordinates.

2. **Frame Overlay:**
   - The visualization function is adapted to overlay multiple frames for a comprehensive view.

     
### Outlier Analysis

1. **Normalization:**
   - Landmark coordinates are normalized based on a reference landmark.

2. **Outlier Identification:**
   - Z-Score is used to identify outliers in the dataset variables.
  
3. **Outlier Injection:**

4. **K-Means Clustering:**
   - K-means clustering is implemented to identify clusters, and outliers are determined based on clustering results.


### Feature Engineering
1. **Principal Component Analysis**
   - Principal Component Analysis (PCA) to reduce dimensionality.
   - Fisher Score is applied to identify relevant features.


###2 part
### Machine Learning

1. **Model Selection:**
   - Appropriate machine learning models are chosen based on the nature of the problem and dataset characteristics.

2. **Training and Evaluation:**
   - Models are trained, evaluated, and fine-tuned using training and validation sets.

3. **Model Interpretation:**
   - Trained models are interpreted to gain insights into the relationships between features and the target variable.


