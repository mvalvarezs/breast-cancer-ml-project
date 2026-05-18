# Breast Cancer Classification using Machine Learning

## Project Description

This project applies Machine Learning techniques to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin Dataset.

The project was developed as part of a Machine Learning course and follows a complete supervised learning methodology including:

- Exploratory Data Analysis (EDA)
- Feature Selection
- Hyperparameter Optimization
- Repeated Cross Validation
- Statistical Comparison of Models
- t-SNE Visualization
- Learning Curves
- Regularization Analysis

---

# Dataset

Dataset used:

Breast Cancer Wisconsin Diagnostic Dataset

Source:
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

---

# Models Implemented

## Base Model
- Regularized Logistic Regression

## Comparative Model
- Linear Support Vector Machine (Linear SVM)

---

# Methodology

The following methodology was implemented:

1. Data loading and preprocessing
2. Exploratory Data Analysis
3. Train/Test split
4. Pipeline construction using sklearn
5. Feature Selection using SelectKBest
6. Hyperparameter optimization using GridSearchCV
7. Repeated Stratified K-Fold Cross Validation
8. Statistical comparison using Wilcoxon Signed-Rank Test
9. t-SNE visualization
10. Final evaluation on test set

---

# Best Hyperparameters

| Hyperparameter | Best Value |
|---|---|
| C | 0.1 |
| k | 25 |

---

# Final Results

## Logistic Regression

- Accuracy: 0.9825
- Precision: 0.9861
- Recall: 0.9861
- F1-score: 0.9861

---

# Statistical Comparison

Wilcoxon Signed-Rank Test:

- p-value = 0.15625

Conclusion:
No statistically significant difference was found between Logistic Regression and Linear SVM.

---

# Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# Repository Structure

```text
├── notebook.ipynb
├── README.md
```

---

# Authors

Marco Alvarez
