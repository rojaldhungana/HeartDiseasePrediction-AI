# Heart Disease Prediction using Machine Learning

## Overview

This project predicts whether a patient is likely to have heart disease using machine learning algorithms. Three classification models were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest

The project was developed as coursework for the Artificial Intelligence module.

---

## Dataset

Dataset: Heart Disease Dataset

Features:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- Slope
- Number of Major Vessels (ca)
- Thalassemia

Target:
- Condition
  - 0 = No Heart Disease
  - 1 = Heart Disease

---

## Project Structure

```
HeartDiseasePrediction/
│
├── data/
├── notebooks/
├── models/
├── outputs/
├── report/
├── presentation/
├── src/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Machine Learning Workflow

1. Load Dataset
2. Data Exploration
3. Data Preprocessing
4. Train-Test Split
5. Feature Scaling
6. Train Models
7. Hyperparameter Tuning
8. Model Evaluation
9. Performance Comparison

---

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score
- Cross Validation

---

## Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 91.67% |
| Random Forest | 88.33% |
| Decision Tree | 78.33% |

The Logistic Regression model achieved the highest accuracy and was selected as the final model.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

---

## Author

Rojal Dhungana

BSc (Hons) Computer Science with Artificial Intelligence

Softwarica College