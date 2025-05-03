# 🍷 Wine Quality Prediction using Machine Learning

This project aims to predict the **quality of wine** (on a scale of 1 to 10) using various physicochemical features and the wine type (red or white). The model helps in classifying wine quality based on measurable properties, which can be useful in wine production and quality assurance processes.

---

## 🔍 Project Overview

- **Objective**: Predict wine quality using supervised machine learning techniques.
- **Dataset**: UCI Wine Quality Dataset (Red & White wine combined with a 'type' feature).
- **Target Variable**: `quality` (integer values from 1 to 10).
- **Best Model**: Random Forest with **91.69% accuracy** (via 10-fold cross-validation).

---

## 🧪 Features Used

| Feature                  | Description                                  |
|--------------------------|----------------------------------------------|
| `type`                  | Wine type: red (0) or white (1)               |
| `fixed acidity`         | Non-volatile acids involved in wine stability |
| `volatile acidity`      | Acetic acid level, causes vinegar taste       |
| `citric acid`           | Adds freshness and flavor                     |
| `residual sugar`        | Sugar left after fermentation                 |
| `chlorides`             | Salt content                                  |
| `free sulfur dioxide`   | SO₂ in free form, protects wine               |
| `total sulfur dioxide`  | Total SO₂ content                             |
| `density`               | Mass per unit volume                          |
| `pH`                    | Acidity level                                 |
| `sulphates`             | Contributes to SO₂ levels and stability       |
| `alcohol`               | Alcohol percentage                            |

---

## 🧠 Models Used

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression
- **Random Forest (Best performer)**

Evaluation was done using **10-fold Cross-Validation**, and accuracy was used as the primary metric.

---

## 📊 Results

| Model               | Accuracy |
|---------------------|----------|
| KNN                 | 85.41%   |
| SVM                 | 71.81%   |
| Logistic Regression | 47.77%   |
| **Random Forest**   | **91.69%** |
