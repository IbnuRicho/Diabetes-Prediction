# 🧠 Diabetes Prediction Using Machine Learning

This project aims to build a **diabetes** prediction model based on patient data using several **Machine Learning** algorithms, then deploy the best model into a **Streamlit** based web application.

---

## 🚀 Project Summary

Patient data is analyzed to predict whether a person has diabetes based on features such as age, gender, hypertension, heart disease, smoking history, BMI, HbA1c levels, and blood glucose levels. The best model used for deployment is **Artificial Neural Network (ANN / MLPClassifier)**.

---

## 📊 Accuracy of Compared Models

| Model | Accuracy |
|--------------------|-----------|
| Logistic Regression| 95.60% |
| Naive Bayes | 90.09% |
| K-Nearest Neighbors| 95.25% |
| **JST (MLPClassifier)** | **95.71% ✅** |

> 🔍 The best model is **JST**, and is used for deployment because it produces the highest accuracy.

---

## 🛠 Technologies Used

- Python
- Streamlit
- scikit-learn
- Pandas
- Pickle (to save the model)
- Jupyter Notebook (for training the model - optional)

---

## 💡 Web Application Features

- Input patient data via form
- Predict whether the patient has diabetes
- Validate predictions based on trained JST models
- Simple and interactive display with **Streamlit**

---

## 🧠 Model Used for Deployment
MLPClassifier (Artificial Neural Network) model has been trained using diabetes dataset. Features used:
- Gender
- Age
- Hypertension
- Heart Disease
- Smoking History
- BMI
- HbA1c Level
- Blood Glucose
  
The model is saved in .sav format using pickle and loaded in app.py.
