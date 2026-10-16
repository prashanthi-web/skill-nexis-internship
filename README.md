# Skill Nexis – Machine Learning and AI Internship

This repository contains the projects, assignments, and practical work completed as part of the Skill Nexis Machine Learning and AI Internship. It documents my learning journey through data preprocessing, supervised learning, regression, classification, unsupervised learning, dimensionality reduction, and model evaluation.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Week 1 – Data Cleaning and Preprocessing](#week-1--titanic-survival-prediction-data-cleaning)
- [Week 2 – Supervised Learning](#week-2--supervised-learning)
- [Week 3 – Unsupervised Learning and Model Evaluation](#week-3--unsupervised-learning-and-model-evaluation)
- [Repository Structure](#repository-structure)
- [Key Learning Outcomes](#key-learning-outcomes)
- [Conclusion](#conclusion)

## Overview

The internship focuses on applying machine learning concepts to practical datasets. Each week's work involves data exploration, implementation using Python libraries, visualization, model building, and analysis of results.

## Technologies Used

- **Programming Language:** Python
- **Data Analysis:** pandas, NumPy
- **Visualization:** Matplotlib
- **Machine Learning:** scikit-learn
- **Model Persistence:** joblib
- **Development Environment:** Jupyter Notebook
- **Version Control:** Git and GitHub

## Week 1 – Titanic Survival Prediction: Data Cleaning

### Objective

Explore and clean the Titanic passenger dataset to prepare it for machine learning.

### Tasks Performed

- Loaded and explored the Titanic dataset.
- Inspected dataset structure and data types.
- Checked for missing values and data quality issues.
- Performed data preprocessing and feature preparation.
- Created a cleaned dataset for further analysis.

### Project Files

Folder: `Week 1- Titanic Survival Prediction/`

- `Titanic-Dataset.csv` – Original dataset.
- `cleaned_titanic.csv` – Cleaned dataset.
- `titanic_survival_predictions.csv` – Survival prediction results.
- `week1_titanic_cleaning.ipynb` – Data cleaning notebook.
- `week2_titanic_logistic_regression.ipynb` – Titanic classification notebook.

### Skills Gained

Data loading, exploratory data analysis, data cleaning, preprocessing, handling categorical features, and preparing datasets for machine learning.

## Week 2 – Supervised Learning

### Objective

Apply supervised machine learning techniques to prediction problems involving regression and classification.

### Topics Covered

- Linear Regression
- Logistic Regression
- Decision Trees and Random Forests
- Model evaluation concepts
- Mean Squared Error (MSE)
- R² score
- Confusion Matrix

### Project 1: Titanic Survival Classification

Applied Logistic Regression to the Titanic dataset to explore passenger survival prediction as a classification problem.

### Project 2: House Price Prediction

Built a regression model to predict house prices using the provided housing dataset.

### Tasks Performed

- Loaded and explored the dataset.
- Prepared features for model training.
- Trained a regression model for house price prediction.
- Generated predicted and actual value comparisons.
- Visualized the model results.

### Project Files

Folder: `Week 2- House Price Prediction/`

- `train.csv` – Housing training dataset.
- `week2_house_price_prediction.ipynb` – House price prediction notebook.
- `output graph.png` – Prediction visualization.

### Skills Gained

Supervised learning, regression, classification, model training, prediction, and visualization of model results.

## Week 3 – Unsupervised Learning and Model Evaluation

### Project: Iris Flower Clustering

### Objective

Apply unsupervised learning techniques to discover patterns and clusters in the Iris flower dataset without using species labels during training.

### Topics Covered

- K-Means Clustering
- Feature Scaling using StandardScaler
- Elbow Method for choosing K
- Principal Component Analysis (PCA)
- Cluster visualization
- Silhouette Score
- Adjusted Rand Index (ARI)
- Saving and loading models using joblib

### Dataset

The Iris dataset contains 150 samples, four numerical features, and three species:

- Setosa
- Versicolor
- Virginica

The project uses the Iris dataset provided by scikit-learn.

### Tasks Performed

1. Loaded and explored the Iris dataset.
2. Standardized the four numerical features.
3. Used the Elbow Method to examine different cluster counts.
4. Applied K-Means clustering with `k=3`.
5. Used PCA to reduce four features to two principal components.
6. Visualized predicted clusters and actual species.
7. Compared cluster assignments with the true labels.
8. Evaluated the results using the Silhouette Score and Adjusted Rand Index.
9. Saved and reloaded the trained model using joblib.

### Project Files

Folder: `Week 3- Iris Flower Clustering/`

- `iris_flower_clustering.ipynb` – Complete clustering notebook.
- `iris_clustering_results.csv` – Dataset features, actual labels, predicted clusters, and PCA coordinates.
- `iris_clusters_pca.png` – PCA cluster visualization.
- `elbow_method.png` – Elbow-method graph.
- `kmeans_iris_model.joblib` – Saved model and preprocessing objects.

### Skills Gained

Unsupervised machine learning, clustering, feature scaling, dimensionality reduction, visualization, cluster evaluation, and model persistence.

## Repository Structure

```text
skill-nexis-internship/
│
├── README.md
│
├── Week 1- Titanic Survival Prediction/
│   ├── Titanic-Dataset.csv
│   ├── cleaned_titanic.csv
│   ├── titanic_survival_predictions.csv
│   ├── week1_titanic_cleaning.ipynb
│   └── week2_titanic_logistic_regression.ipynb
│
├── Week 2- House Price Prediction/
│   ├── train.csv
│   ├── output graph.png
│   └── week2_house_price_prediction.ipynb
│
└── Week 3- Iris Flower Clustering/
    ├── iris_flower_clustering.ipynb
    ├── iris_clustering_results.csv
    ├── iris_clusters_pca.png
    ├── elbow_method.png
    └── kmeans_iris_model.joblib
```

## Key Learning Outcomes

Through these projects, I have gained practical experience in:

- Loading, inspecting, and cleaning datasets.
- Performing exploratory data analysis.
- Preparing features for machine learning.
- Understanding regression and classification.
- Training and evaluating machine learning models.
- Applying K-Means clustering to unlabeled data.
- Reducing feature dimensions using PCA.
- Visualizing data and model predictions.
- Saving and reloading trained machine learning models.
- Organizing projects and maintaining code using Git and GitHub.

## Conclusion

The Skill Nexis Machine Learning and AI Internship provides practical exposure to data analysis and machine learning workflows. The projects demonstrate progressive learning from data cleaning and supervised prediction to unsupervised clustering and dimensionality reduction.

This repository will be updated as additional internship assignments and projects are completed.