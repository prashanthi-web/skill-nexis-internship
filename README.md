# House Price Prediction Model

## Week 2 – Machine Learning & AI Internship

### Project Overview
This project builds a Machine Learning model using **Linear Regression** to predict house sale prices based on important housing features. It demonstrates data preprocessing, model training, prediction, and evaluation.

### Objectives
- Understand supervised learning and regression.
- Train a Linear Regression model using housing data.
- Predict house prices using selected features.
- Evaluate model performance using the R² score and Mean Squared Error (MSE).
- Visualize actual versus predicted house prices.

### Dataset
**House Prices: Advanced Regression Techniques – Kaggle**

Dataset: `train.csv`

Target variable: `SalePrice`

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### Features Used
The following numerical features were selected for training:

- `OverallQual` – Overall house quality
- `GrLivArea` – Above-ground living area
- `GarageCars` – Garage capacity
- `TotalBsmtSF` – Total basement area
- `1stFlrSF` – First-floor area
- `FullBath` – Number of full bathrooms
- `YearBuilt` – Year the house was built

### Project Workflow
1. Loaded the housing dataset using Pandas.
2. Explored the dataset using `info()` and `describe()`.
3. Selected relevant numerical features.
4. Handled missing values in the selected features using median imputation.
5. Split the dataset into training and testing sets.
6. Trained a Linear Regression model.
7. Predicted house prices for the test dataset.
8. Evaluated predictions using R² score and MSE.
9. Plotted actual versus predicted house prices.

### Model Evaluation
The model was evaluated using:

- **R² Score:** Measures how much variation in house prices is explained by the model.
- **Mean Squared Error (MSE):** Measures the average squared difference between actual and predicted prices.

The model achieved an R² score of approximately **0.7955** in the current evaluation run. This indicates that it explains about 79.55% of the variation in house prices in the test set.

### Visualization
The project includes an **Actual vs. Predicted House Prices** scatter plot to visualize model performance.

### Project Files
- `train.csv` – Housing dataset
- `week2_house_price_prediction.ipynb` – Notebook containing preprocessing, model training, evaluation, and visualization
- `README.md` – Project documentation

### Conclusion
This project demonstrates the application of supervised Machine Learning using Linear Regression for house price prediction. It provides practical experience with data preprocessing, training/testing splits, regression evaluation metrics, and visualization.

### Author
Machine Learning & AI Internship – Week 2
