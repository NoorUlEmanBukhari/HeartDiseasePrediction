# ❤️ Heart Disease Prediction using Machine Learning

This project aims to build a predictive model that can accurately determine whether a person is at risk of heart disease based on various medical attributes. Early prediction can help in timely diagnosis and potentially save lives.

## 📁 Project Overview

Cardiovascular diseases are the leading cause of death globally. Using machine learning algorithms, we analyze patient data and classify individuals as having or not having heart disease.

## 📊 Dataset

- **Attributes**: 14 features including:
  - age`, `sex`, `cp`, `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`, `target`
- **Target**:
  - 0` – No heart disease
  - 1` – Presence of heart disease

## 🛠️ Tools & Technologies

- **Language**: Python
- **Libraries**:
  - pandas, numpy – data handling
  - matplotlib, seaborn – visualization
  - scikit-learn – model training and evaluation
  - XGBoost` / Random Forest / Logistic Regression – classification models

## 🚀 Project Pipeline

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix
   - Feature distribution
   - Target class imbalance

3. **Model Training**
   - Train/test split
   - Baseline model
   - Advanced models (e.g., XGBoost, SVM)

4. **Evaluation Metrics**
   - Accuracy
   - Confusion Matrix
   - Precision, Recall, F1-Score
   - ROC Curve & AUC


## 📈 Results

- Best model: **Logistic Regression**, **RandomForestClassifier**, **XGBClassifier**
- Accuracy: **82%**
- ROC-AUC: ** 0.91**

## 📌 How to Run

1. Clone the repository:
   ```bash
 git clone https://github.com/NoorUlEmanBukhari/heart-disease-prediction.git
 cd heart-disease-prediction
