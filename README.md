# 🩺 Diabetes Prediction using Machine Learning

## 📌 Project Overview

This project builds a Machine Learning model to predict whether a person has diabetes based on demographic and medical information. The workflow includes data preprocessing, exploratory data analysis (EDA), handling class imbalance using SMOTE, model training, and performance evaluation.

---

## 📊 Dataset

The dataset contains **100,000 patient records** with **9 features**.

### Features

| Feature | Description |
|---------|-------------|
| gender | Patient gender |
| age | Patient age |
| hypertension | Hypertension status (0/1) |
| heart_disease | Heart disease status (0/1) |
| smoking_history | Smoking history |
| bmi | Body Mass Index |
| HbA1c_level | HbA1c blood sugar level |
| blood_glucose_level | Blood glucose level |
| diabetes | Target variable (0 = No Diabetes, 1 = Diabetes) |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## ⚙️ Project Workflow

- Data Loading
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Encoding Categorical Features
- Feature Scaling
- Train-Test Split
- Handle Class Imbalance using SMOTE
- Train Multiple Machine Learning Models
- Model Evaluation

---

## 🤖 Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

## 📁 Project Structure

```
project_diabetes/
│── Copy_of_ML_project_done.ipynb
│── diabetes_prediction_dataset.csv
│── README.md
│── requirements.txt
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/MohamedElashry18/project_diabetes.git
cd project_diabetes
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📊 Results

The models were evaluated using multiple classification metrics. SMOTE was applied to address class imbalance, improving the model's ability to detect diabetic cases (higher Recall) while maintaining strong overall performance.

---

## 👨‍💻 Author

**Mohamed Elashry**

Faculty of Artificial Intelligence  
Kafrelsheikh University

GitHub: https://github.com/MohamedElashry18
