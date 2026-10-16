# Skill Nexis — Machine Learning & Artificial Intelligence Internship

A collection of weekly assignments and machine learning projects completed as part of the Skill Nexis Machine Learning & Artificial Intelligence Internship.

This repository documents the learning journey from data cleaning and supervised learning to unsupervised learning, clustering, model evaluation, and visualization.

## Internship Overview

**Domain:** Machine Learning & Artificial Intelligence  
**Programming Language:** Python  
**Tools:** Jupyter Notebook, Git, GitHub  
**Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn, Joblib

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
├── Week 3- Iris Flower Clustering/
│   ├── iris_flower_clustering.ipynb
│   ├── iris_clustering_results.csv
│   ├── iris_clusters_pca.png
│   ├── elbow_method.png
│   └── kmeans_iris_model.joblib
│
└── Week 4- Customer Segmentation/
    ├── Mall_Customers.csv
    ├── customer_segmentation.ipynb
    ├── elbow_method.png
    ├── customer_segments_income_spending.png
    ├── customer_segments_3d.png
    ├── customer_segment_summary.csv
    ├── customer_segmentation_results.csv
    └── customer_segmentation_model.joblib
```

*Note: The structure above describes the intended project files. Keep only files that actually exist in your repository.*

---

## Week 1 — Titanic Survival Prediction: Data Cleaning

### Objective
Explore and clean the Titanic passenger dataset to prepare it for machine learning.

### Work Completed
- Loaded and explored the Titanic dataset using Pandas.
- Inspected column names, data types, and missing values.
- Performed data cleaning and prepared the dataset for analysis.
- Applied one-hot encoding to the `Embarked` categorical feature.
- Exported the cleaned dataset for further use.

### Technologies
Python, Pandas, NumPy, Jupyter Notebook.

### Project Files
- `Titanic-Dataset.csv` — source dataset.
- `cleaned_titanic.csv` — cleaned dataset.
- `week1_titanic_cleaning.ipynb` — data cleaning and exploration notebook.
- `titanic_survival_predictions.csv` — prediction output, if generated.

### Learning Outcomes
- Understanding tabular data.
- Inspecting and preparing datasets.
- Handling categorical features.
- Building a repeatable data preprocessing workflow.

---

## Week 2 — Supervised Machine Learning

This week covers supervised learning through classification and regression tasks.

### Project 1: Titanic Survival Prediction Using Logistic Regression

#### Objective
Build a classification model to predict passenger survival from the Titanic dataset.

#### Work
- Prepared features for classification.
- Used Logistic Regression to predict survival.
- Explored supervised learning concepts and model predictions.

#### Project File
`week2_titanic_logistic_regression.ipynb`

### Project 2: House Price Prediction

#### Objective
Build a regression model to estimate house prices using housing data.

#### Work
- Loaded and explored the housing dataset.
- Prepared data for regression.
- Trained a regression model.
- Compared predicted and actual values through a visualization.

#### Project Files
- `train.csv` — housing training dataset.
- `week2_house_price_prediction.ipynb` — model implementation.
- `output graph.png` — prediction visualization.

### Technologies
Python, Pandas, NumPy, Matplotlib, Scikit-learn.

### Learning Outcomes
- Understanding supervised learning.
- Exploring classification and regression.
- Training machine learning models.
- Visualizing model predictions.
- Interpreting model performance.

---

## Week 3 — Iris Flower Clustering

### Objective
Apply unsupervised machine learning to group Iris flowers based on their numerical features.

### Work
- Loaded the Iris dataset.
- Prepared and standardized numerical features.
- Used the Elbow Method to examine possible cluster counts.
- Applied K-Means clustering.
- Used Principal Component Analysis (PCA) to visualize clusters in two dimensions.
- Compared the predicted clusters with known species labels for analysis.
- Exported clustering results and saved the trained model.

### Technologies
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Joblib.

### Project Files
- `iris_flower_clustering.ipynb` — complete notebook.
- `iris_clustering_results.csv` — clustering results.
- `iris_clusters_pca.png` — PCA cluster visualization.
- `elbow_method.png` — Elbow Method plot.
- `kmeans_iris_model.joblib` — saved model, if generated.

### Learning Outcomes
- Understanding unsupervised learning.
- Applying K-Means clustering.
- Using feature scaling.
- Exploring dimensionality reduction with PCA.
- Visualizing and evaluating clusters.

---

## Week 4 — Customer Segmentation Using K-Means Clustering

**Final Internship Project**

### Objective
Group mall customers into segments based on age, annual income, and spending score using unsupervised machine learning.

Customer segmentation helps businesses explore customer behavior and develop more targeted marketing strategies.

### Dataset
**Mall Customers Dataset**

Source: [Kaggle — Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)

### Features Used
- **Age:** Customer age.
- **Annual Income (k$):** Annual income represented in thousands of dollars.
- **Spending Score (1–100):** Spending score provided in the dataset.

### Methodology

1. Load and inspect the dataset using Pandas.
2. Check for duplicate records and missing values.
3. Prepare the numerical features.
4. Standardize features using `StandardScaler`.
5. Apply the Elbow Method to examine the number of clusters.
6. Train a K-Means model using three clusters.
7. Calculate the Silhouette Score to evaluate cluster separation.
8. Assign descriptive spending-level labels based on average cluster spending scores.
9. Visualize the customer groups.
10. Export customer-level results and segment summaries.
11. Save and reload the trained model using Joblib.

### Technologies
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Joblib, Jupyter Notebook.

### Project Files

| File | Description |
|---|---|
| `customer_segmentation.ipynb` | Complete implementation |
| `Mall_Customers.csv` | Input dataset |
| `elbow_method.png` | Elbow Method visualization |
| `customer_segments_income_spending.png` | Annual income versus spending visualization |
| `customer_segments_3d.png` | Three-dimensional customer visualization |
| `customer_segment_summary.csv` | Summary statistics for each segment |
| `customer_segmentation_results.csv` | Customer-level clustering results |
| `customer_segmentation_model.joblib` | Saved scaler, K-Means model, features, and segment labels |

### Customer Segments

The implementation creates three clusters and labels them according to their average spending scores:

- **Low Spenders:** Cluster with the lowest average spending score.
- **Medium Spenders:** Cluster with the middle average spending score.
- **High Spenders:** Cluster with the highest average spending score.

These names describe relative spending behavior within the generated clusters. They do not necessarily indicate profitability or overall customer value.

### Evaluation
- **Elbow Method:** Helps examine how the within-cluster sum of squares changes with the number of clusters.
- **Silhouette Score:** Measures how well-separated the clusters are.
- **Visualizations:** Help explore relationships between income, spending score, and age.

The actual Silhouette Score and segment statistics are available from the executed notebook and exported CSV files.

### Learning Outcomes
- Applying unsupervised machine learning to customer data.
- Understanding K-Means clustering.
- Standardizing numerical features.
- Exploring cluster evaluation methods.
- Creating two-dimensional and three-dimensional visualizations.
- Exporting model predictions and summary statistics.
- Saving and reloading a trained machine learning model.

### Conclusion
This project demonstrates how K-Means clustering can organize customers into spending-based groups. The resulting segments can help businesses explore purchasing behavior and investigate potential marketing strategies.

---

## Skills Developed During the Internship

- Python programming for data analysis.
- Data loading, inspection, and cleaning.
- Handling numerical and categorical data.
- Supervised learning: classification and regression.
- Unsupervised learning: K-Means clustering.
- Feature standardization.
- Model evaluation and visualization.
- Dimensionality reduction using PCA.
- Exporting results to CSV.
- Saving machine learning models with Joblib.
- Using Jupyter Notebook, Git, and GitHub.

## How to Run the Projects

### 1. Clone the repository

```bash
git clone https://github.com/prashanthi-web/skill-nexis-internship.git
cd skill-nexis-internship
```

### 2. Install the required libraries

```bash
python -m pip install pandas numpy matplotlib scikit-learn joblib jupyter
```

### 3. Launch Jupyter Notebook

```bash
python -m jupyter notebook
```

Open the notebook for the week you want to explore and execute the cells in order.

**Note:** Some projects may require their corresponding datasets to be downloaded separately. Check each notebook for the expected file names and any additional dependencies.

## Repository

GitHub: [prashanthi-web/skill-nexis-internship](https://github.com/prashanthi-web/skill-nexis-internship)

---

*This repository documents the weekly assignments and projects completed during the Skill Nexis Machine Learning & Artificial Intelligence Internship.*
