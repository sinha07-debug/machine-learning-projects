# Heart Disease Prediction using Decision Tree Classifier

## Overview

This project implements a Decision Tree Classifier to predict heart disease using patient medical data. The project demonstrates a complete machine learning workflow including preprocessing, model training, evaluation, visualization, and hyperparameter tuning.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Dataset

The dataset contains medical information such as:

* age
* sex
* chest pain type (`cp`)
* cholesterol
* maximum heart rate (`thalach`)
* oldpeak
* thalassemia (`thal`)
* and other cardiac-related attributes

Target:

* `1` → Heart Disease
* `0` → No Heart Disease

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Remove Duplicate Rows
5. Feature and Target Separation
6. Train-Test Split
7. Train Decision Tree Classifier
8. Evaluate Model Performance
9. Visualize Decision Tree
10. Analyze Feature Importance
11. Hyperparameter Tuning
12. Compare Gini vs Entropy
13. Plot ROC Curve and Decision Boundary

---

## Model Evaluation Metrics

The following metrics were used:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC Score
* Confusion Matrix

---

## Important Findings

* Duplicate rows initially caused unrealistically high accuracy.
* Removing duplicates improved evaluation reliability.
* Increasing tree depth improved training accuracy but eventually caused overfitting.
* Chest pain type (`cp`) was the most important predictive feature.
* Gini criterion slightly outperformed entropy on the cleaned dataset.

---

## Visualizations Included

* Confusion Matrix
* Decision Tree Plot
* Feature Importance Graph
* Depth vs Accuracy Graph
* ROC Curve
* Decision Boundary Plot

---

## Future Improvements

* Random Forest Classifier
* Cross Validation
* GridSearchCV

---

