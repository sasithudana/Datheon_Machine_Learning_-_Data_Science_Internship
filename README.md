# Datheon_Machine_Learning_&_Data_Science_Internship
# Datheon Machine Learning – Data Science Internship

<p align="center">
  **Machine Learning | Data Science | Predictive Modeling**
</p>

## About This Repository

This repository showcases the machine learning projects completed as part of my **Datheon Machine Learning – Data Science Internship**.

The internship provided hands-on experience in applying supervised machine learning techniques to real-world and benchmark datasets. Through these projects, I explored data preprocessing, exploratory data analysis, feature engineering, model development, hyperparameter tuning, and model evaluation.

The repository contains three projects covering classification, regression, and customer churn prediction.

---

## Projects

### 1. Multiclass Benchmark Classification Pipeline

**Problem Type:** Supervised Machine Learning – Classification

**Dataset:** Iris / Wine Dataset

**Objective:**

Implement and benchmark supervised classification models to classify observations into multiple target classes using benchmark datasets.

**Key Tasks:**
- Load and explore the benchmark dataset using Pandas.
- Perform Exploratory Data Analysis (EDA) using Seaborn pairplots.
- Split the dataset into training and testing sets (80/20).
- Standardize features using `StandardScaler`.
- Train Logistic Regression and Decision Tree classifiers.
- Compare classification model performance.

**Models Implemented:**
- Logistic Regression
- Decision Tree Classifier

**Evaluation Metrics:**
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

**Visualizations:**
- Exploratory pairplots
- Confusion matrix heatmap
- Decision boundary visualization

**Technologies:** Python, Pandas, Scikit-Learn, Seaborn, Matplotlib

---

### 2. Real Estate Housing Price Prediction

**Problem Type:** Supervised Machine Learning – Regression

**Dataset:** California Housing Dataset

**Objective:**

Develop regression models to predict median house values using housing-related features while applying feature engineering, regularization, and model optimization techniques.

**Key Tasks:**
- Load and explore the California Housing dataset.
- Handle missing values using imputation techniques.
- Perform correlation analysis using heatmaps.
- Engineer interaction features.
- Investigate and handle multicollinearity.
- Standardize continuous variables and encode categorical attributes.
- Train and compare different regression models.
- Optimize model hyperparameters using `GridSearchCV`.

**Models Implemented:**
- Ordinary Least Squares (OLS) – Linear Regression
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)

**Hyperparameter Optimization:**

Apply `GridSearchCV` to identify suitable alpha values for Ridge and Lasso regression models.

**Evaluation Metrics:**
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-Squared (R²)

**Visualizations:**
- Correlation heatmap
- Actual vs. Predicted values
- Residual distribution plots

**Technologies:** Python, Pandas, Scikit-Learn, LinearRegression, Ridge, Lasso, GridSearchCV, Matplotlib, Seaborn

---

### 3. Predictive Customer Churn Classifier

**Problem Type:** Supervised Machine Learning – Classification

**Dataset:** Telco Customer Churn Dataset

**Objective:**

Develop an ensemble machine learning model to predict customer churn using telecom subscription records and identify customers who are likely to discontinue their services.

**Key Tasks:**
- Load and explore the Telco Customer Churn dataset.
- Convert `TotalCharges` into numeric format.
- Handle missing values.
- Preprocess categorical variables using `OneHotEncoder`.
- Address class imbalance using SMOTE or class weighting.
- Train ensemble classification models.
- Perform cross-validation to evaluate model performance.
- Analyze important features influencing customer churn.

**Models Implemented:**
- Random Forest Classifier
- XGBoost Classifier

**Model Optimization:**

Use cross-validation and appropriate class-balancing techniques to improve classification performance.

**Evaluation Metrics:**
- ROC-AUC Score
- Classification Performance Metrics
- ROC Curve

**Target Performance:** ROC-AUC greater than 0.80.

**Visualizations:**
- ROC-AUC curves
- Top 10 feature importance visualization

**Technologies:** Python, Pandas, Scikit-Learn, Random Forest, XGBoost, SMOTE, Matplotlib, Seaborn

---

## Technical Skills & Tools

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Classification | Logistic Regression, Decision Tree, Random Forest, XGBoost |
| Regression | Linear Regression, Ridge, Lasso |
| Data Preprocessing | StandardScaler, OneHotEncoder, Imputation |
| Model Optimization | GridSearchCV, Cross-Validation |
| Model Evaluation | Accuracy, Precision, Recall, F1-Score, RMSE, MAE, R², ROC-AUC |
| Class Balancing | SMOTE, Class Weighting |

---

## Key Learning Outcomes

Through these projects, I gained practical experience in:

- Applying supervised machine learning algorithms to classification and regression problems.
- Performing exploratory data analysis and data visualization.
- Handling missing values and preprocessing numerical and categorical features.
- Implementing feature scaling, feature engineering, and encoding techniques.
- Building and comparing multiple machine learning models.
- Applying regularization techniques to improve regression models.
- Handling imbalanced datasets in classification problems.
- Performing hyperparameter tuning and cross-validation.
- Evaluating model performance using appropriate metrics and visualizations.

---

## Repository Structure

```text
Datheon_Machine_Learning_-_Data_Science_Internship/
│
├── Multiclass-Benchmark Classification Pipeline/
│   └── README.md
│
├── Predictive Customer Churn Classifier/
│   └── README.md
│
├── Real Estate Housing Price Prediction/
│   └── README.md
│
└── README.md
```

---

## Internship Information

**Organization:** Datheon

**Domain:** Machine Learning & Data Science

**Internship Focus:** Supervised Learning, Classification, Regression, and Predictive Analytics

**Repository Owner:** Sasith Udana

---

Thank you for visiting my repository!

Feel free to explore the individual project folders to learn more about the implementations and machine learning workflows.
