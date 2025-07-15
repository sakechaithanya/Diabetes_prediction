
# 🩺 Diabetes Prediction - Classification Project

This project is a machine learning classification model to **predict whether a person is diabetic or not** based on health-related attributes such as age, BMI, blood glucose levels, and smoking history.

## 🔍 Problem Statement

Given a dataset containing patient details, the goal is to predict the presence of **diabetes** (`0 = non-diabetic`, `1 = diabetic`) using classification algorithms. The model aims to support early detection based on accessible medical and lifestyle indicators.

---

## 📁 Dataset

- **Source**: [Kaggle or Custom Dataset]
- **Features**:
  - `age`
  - `hypertension`
  - `heart_disease`
  - `bmi`
  - `HbA1c_level`
  - `blood_glucose_level`
  - `smoking_history` (One-Hot Encoded: `never`, `current`, `former`, `ever`, `not current`, `No Info`)
- **Target**: `diabetes` (binary: 0 = non-diabetic, 1 = diabetic)

---

## 🧠 ML Workflow

1. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Applied one-hot encoding to categorical columns
   - Standardized numerical features using `StandardScaler`

2. **Model Building**
   - Used `Logistic Regression` for binary classification
   - Trained on labeled patient records

3. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

4. **Prediction Function**
   - Custom function `predict_diabetes()` takes input values, scales them, and outputs prediction

---

## 📦 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualizations)
- Jupyter Notebook
- (Optional) Flask – for web deployment
