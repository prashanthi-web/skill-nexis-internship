# Skill Nexis – Machine Learning & AI Internship

This repository documents my learning journey, weekly assignments, and hands-on projects completed as part of the **Skill Nexis Machine Learning & AI Internship**.

The internship provides practical experience in data preprocessing, exploratory data analysis, supervised machine learning, regression, classification, model evaluation, and data visualization using Python.

## 🎯 Internship Objectives

- Understand fundamental Machine Learning and AI concepts.
- Perform data cleaning and preprocessing on real-world datasets.
- Explore datasets using statistical analysis and visualization.
- Build regression and classification models.
- Evaluate model performance using appropriate metrics.
- Apply machine learning concepts through practical assignments and mini-projects.
- Maintain and document project work using Git and GitHub.

## 🛠️ Technologies and Tools

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook
- **Version Control:** Git, GitHub
- **Datasets:** Titanic Dataset and Kaggle House Prices Dataset

## 📂 Repository Structure

```text
skill-nexis-internship/
│
├── Week 1- Titanic Survival Prediction/
│   ├── week1_titanic_cleaning.ipynb
│   ├── week2_titanic_logistic_regression.ipynb
│   ├── Titanic-Dataset.csv
│   ├── cleaned_titanic.csv
│   └── titanic_survival_predictions.csv
│
├── Week 2- House Price Prediction/
│   ├── week2_house_price_prediction.ipynb
│   ├── train.csv
│   └── output graph.png
│
└── README.md
```

*The structure above represents the intended organization. Actual filenames and locations may differ depending on the files saved locally.*

---

## 📅 Internship Progress and Projects

### Week 1 – Data Cleaning and Preprocessing

**Project: Titanic Dataset Data Cleaning**

**Objective:** Clean and prepare the Titanic passenger dataset for analysis and machine learning.

**Tasks completed:**
- Loaded the dataset using Pandas.
- Explored dataset dimensions, column types, and descriptive statistics.
- Identified missing values in the dataset.
- Filled missing `Age` values using the median.
- Filled missing `Embarked` values using the mode.
- Removed the `Cabin` column because it contained extensive missing data.
- Encoded categorical variables, including passenger sex and embarkation port.
- Visualized age distribution using a histogram.
- Exported the cleaned dataset to a CSV file.
- Verified that the cleaned dataset contained no remaining missing values.

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.

**Learning outcome:** Gained practical experience in data exploration, handling missing values, categorical encoding, and preparing data for machine learning.

### Week 2 – Assignment 1: House Price Prediction

**Project: House Price Prediction Model**

**Objective:** Predict house sale prices using a Linear Regression model trained on the Kaggle House Prices dataset.

**Tasks completed:**
- Loaded and explored the housing dataset.
- Selected relevant numerical features, including overall quality, living area, garage capacity, basement area, first-floor area, full bathrooms, and year built.
- Prepared input features and the target variable, `SalePrice`.
- Split the dataset into training and testing sets.
- Trained a Linear Regression model.
- Generated house price predictions.
- Evaluated the model using R² score and Mean Squared Error (MSE).
- Created an actual-versus-predicted visualization.

**Evaluation metrics:**
- **R² Score:** Approximately 0.7955, as previously reported.
- **Mean Squared Error (MSE):** Approximately 1,568,368,656.55, as previously reported.

*These values should be verified against the final notebook run before being treated as final results.*

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.

**Learning outcome:** Practiced regression modelling, feature selection, train-test splitting, price prediction, and regression evaluation.

### Week 2 – Assignment 2: Titanic Survival Prediction

**Project: Titanic Survival Classification using Logistic Regression**

**Objective:** Predict whether a Titanic passenger survived using a supervised classification algorithm.

**Tasks completed:**
- Loaded and explored the Titanic dataset.
- Selected passenger class, sex, age, family details, fare, and embarkation port as model features.
- Handled missing values in the age and embarkation columns.
- Encoded categorical variables using one-hot encoding.
- Split the dataset into training and testing sets, using an 80:20 ratio.
- Trained a Logistic Regression model.
- Predicted survival outcomes for the test dataset.
- Evaluated the model using accuracy, a classification report, and a confusion matrix.
- Visualized actual and predicted survival values.
- Saved prediction results to a CSV file.

**Evaluation metrics:**
- Accuracy: To be recorded from the final notebook execution.
- Classification report: Precision, recall, and F1-score.
- Confusion matrix: Comparison of actual and predicted classes.

**Tools:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn.

**Learning outcome:** Practiced classification, categorical feature encoding, model training, prediction, and classification evaluation.

---

## 📊 Machine Learning Concepts Practiced

| Concept | Application |
|---|---|
| Data cleaning | Titanic dataset |
| Missing value handling | Age and embarkation data |
| Categorical encoding | Sex and Embarked |
| Exploratory data analysis | Titanic and house prices |
| Linear Regression | House price prediction |
| Logistic Regression | Titanic survival prediction |
| Train-test split | Model validation |
| R² score and MSE | Regression evaluation |
| Accuracy and confusion matrix | Classification evaluation |
| Data visualization | Histograms, prediction plots, and confusion matrix |

## 📚 Key Learnings So Far

- Loading, inspecting, and cleaning datasets using Pandas.
- Handling missing values and encoding categorical data.
- Performing exploratory data analysis.
- Selecting relevant features for machine learning.
- Building regression and classification models with Scikit-learn.
- Splitting datasets into training and testing sets.
- Making predictions and evaluating model performance.
- Visualizing model outputs and saving results.
- Organizing project files and documenting work with GitHub.

## 🚀 Future Improvements

- Complete and validate all model evaluation results.
- Experiment with Decision Tree and Random Forest algorithms.
- Explore additional feature engineering techniques.
- Compare different models and improve predictive performance.
- Document upcoming weekly assignments and mini-projects as the internship progresses.

## 👩‍💻 Author

**Prashanthi Valusa**

- GitHub: [prashanthi-web](https://github.com/prashanthi-web)

## Acknowledgment

Thanks to **Skill Nexis** for providing the opportunity to develop practical skills in Machine Learning and AI through structured learning, assignments, and mini-projects.

---

*This repository will be updated throughout the internship to document additional assignments, projects, and learning outcomes.*
