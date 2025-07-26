# SVM-Diabetes-prediction

#  Diabetes Prediction using Custom SVM (Support Vector Machine)

This project implements a Support Vector Machine (SVM) from scratch in Python to predict whether a patient is diabetic or not, based on medical features. The goal is to provide a deep understanding of how SVM works internally, without relying on libraries like scikit-learn.

---

Dataset

The model uses the **Pima Indians Diabetes Dataset**, which contains medical diagnostic information for women of Pima Indian heritage.  
Each row in the dataset represents a patient and includes the following features:

- `Pregnancies`
- `Glucose`
- `BloodPressure`
- `SkinThickness`
- `Insulin`
- `BMI`
- `DiabetesPedigreeFunction`
- `Age`

The target label (`Outcome`) is:
- `1` – Diabetic
- `0` – Non-diabetic

---
Model: SVM from Scratch

The custom implementation includes:

- **Linear SVM classifier**
- **Hinge loss function**
- **L2 Regularization**
- **Gradient Descent optimizer**

Parameters

- `alpha`: Learning rate
- `iteration`: Number of gradient descent steps
- `lambda`: Regularization parameter

