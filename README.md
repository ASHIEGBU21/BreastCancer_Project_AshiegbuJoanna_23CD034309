# Breast Cancer Prediction System

## Project Overview
This project is a machine learning-based Breast Cancer Prediction System developed
for educational purposes. It predicts whether a tumor is **Benign** or **Malignant**
based on selected features from the Breast Cancer Wisconsin (Diagnostic) dataset.

⚠️ **Disclaimer:** This system is strictly for educational purposes and must not be
used as a medical diagnostic tool.

---

## Dataset
Breast Cancer Wisconsin (Diagnostic) Dataset  
Features used in this project:
- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Concavity

Target variable:
- Diagnosis (Benign / Malignant)

---

## Machine Learning Model
- Algorithm: Logistic Regression
- Feature Scaling: StandardScaler
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

The trained model and scaler are saved using Joblib and reused for prediction
without retraining.

---

## Web Application
A Flask-based web application is used to provide a graphical user interface (GUI)
for the prediction system. Users can input tumor feature values and receive
prediction results.

---

## Technologies Used
- Python
- Scikit-learn
- Flask
- HTML/CSS
- Joblib
- NumPy
- Pandas

---

## Project Structure
# BreastCancer_Project_AshiegbuJoanna_23CD034309
# BreastCancer_Project_AshiegbuJoanna_23CD034309
