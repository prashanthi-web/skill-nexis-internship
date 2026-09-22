# Titanic Survival Prediction – Data Cleaning Project

## Week 1 – Machine Learning & AI Internship

### Objective

The objective of this project is to practice basic machine learning
data preprocessing techniques using the Titanic dataset.

### Tasks Completed

- Loaded the Titanic dataset using Pandas
- Explored the dataset using `info()` and `describe()`
- Checked for missing values
- Handled missing Age values using median imputation
- Handled missing Embarked values using mode imputation
- Removed the Cabin column because of a large number of missing values
- Encoded Sex using LabelEncoder
- Encoded Embarked using OneHotEncoder
- Visualized the Age distribution using Matplotlib and Seaborn
- Exported the cleaned dataset as a CSV file

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### Files

- `Titanic-Dataset.csv` – Original dataset
- `week1_titanic_cleaning.ipynb` – Data cleaning and analysis notebook
- `cleaned_titanic.csv` – Cleaned dataset

### Result

The dataset was successfully cleaned, categorical variables were encoded,
and the final processed dataset was exported as `cleaned_titanic.csv`.