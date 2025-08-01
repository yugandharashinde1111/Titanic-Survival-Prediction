# 🚢 Titanic Survival Prediction

This project uses machine learning to predict passenger survival from the Titanic dataset.  
It includes **Exploratory Data Analysis (EDA)**, **feature engineering**, and **model building** using Python.

---

## 🔧 Technologies Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📊 Features
- Exploratory Data Analysis with visualizations
- Handling missing values (Age, Fare, Cabin)
- Feature Engineering:
  - Encoded categorical variables (Pclass, Sex, Embarked)
  - Created new feature: **Family Size**
  - Feature scaling (Age, Fare, Family)
- Model Training:
  - Logistic Regression
  - Decision Tree
- Model Evaluation:
  - Accuracy, Precision, Recall, F1-score
  - Confusion Matrix & Classification Report

---

## 📁 Files
- `Titanic_Survival_Prediction.ipynb` – Main Jupyter Notebook
- `requirements.txt` – Dependencies
- `train.csv` – Dataset (or link from Kaggle)
- `README.md` – Project overview

---

## 🔗 Dataset
[Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

---

## 🚀 Future Improvements
- Add Random Forest / XGBoost models
- Hyperparameter tuning
- Deploy model using Flask or Streamlit
