# Data-Driven Workforce Analytics & Attrition Prediction

## 🧠 Employee Attrition Prediction

This project focuses on predicting employee attrition using machine learning algorithms and scikit-learn pipelines. It is a practice project aimed at understanding and implementing the entire ML lifecycle—from preprocessing to evaluation—while maintaining clean, reusable code using pipelines.


## 🔍 Problem Statement

The goal is to identify the factors that lead to employee attrition in a company and to build a predictive model that can classify whether an employee is likely to leave.

---

## 🚀 Project Workflow

### 1. 📥 Data Collection
- Dataset used: IBM HR Analytics Employee Attrition & Performance dataset.
- Source: [Kaggle Dataset](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

### 2. 🧹 Data Preprocessing
- Handled missing values (if any).
- Encoded categorical features using `OneHotEncoder`.
- Scaled numerical features using `StandardScaler`.
- Feature selection based on correlation and domain understanding.

### 3. 🏗️ ML Pipeline Creation
Implemented modular pipelines for:
- Preprocessing (using `ColumnTransformer`)
- Model training
- Evaluation

### 4. 🤖 Model Training
Practiced and compared the following ML algorithms:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting (Optional / Bonus)

### 5. 📊 Model Evaluation
Used metrics like:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- Cross-validation scores

### 6. 🧪 Hyperparameter Tuning
Used `GridSearchCV` or `RandomizedSearchCV` for parameter optimization.

## Folders
- `data/` — Contains raw and cleaned datasets
- `notebooks/` — Google Colab notebooks for EDA and modeling
- `src/` — (Optional) Python scripts for modular code


