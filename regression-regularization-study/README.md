# Regression & Regularization Study

A comprehensive statistical learning study covering linear regression, regression diagnostics, regularization, nonlinear regression, and the bias-variance trade-off.

## Overview

This project explores several core concepts in statistical learning through controlled simulations and regression experiments.

The analysis is divided into three main sections:

1. **Linear Regression & Model Diagnostics**
2. **Shrinkage & Regularization**
3. **Nonlinear Regression & Bias-Variance**

The experiments demonstrate how model complexity, regularization, and sample size affect model fitting and generalization.

## Objectives

* Simulate and analyze a linear regression dataset.
* Fit an Ordinary Least Squares (OLS) model.
* Evaluate regression assumptions using diagnostic techniques.
* Understand the effect of regularization on model coefficients.
* Compare Ridge, Lasso, and Elastic-Net regression.
* Demonstrate underfitting and overfitting using polynomial regression.
* Study the bias-variance trade-off.
* Compare polynomial regression with decision-tree regression.

## Methodology

### 1. Linear Regression & Diagnostics

A simulated dataset containing **300 observations and 10 predictors** was generated from a linear model.

The analysis includes:

* Ordinary Least Squares (OLS)
* Coefficient estimation
* Statistical significance
* Residual analysis
* Normality assessment
* Homoscedasticity assessment
* Leverage and influential observations

The simulated dataset contains strong, weak, and null predictors, allowing the ability of OLS to recover the underlying signal to be examined.

### 2. Regularization

Three regularized regression techniques were compared.

#### Ridge Regression

Ridge applies an L2 penalty and continuously shrinks coefficients toward zero.

#### Lasso Regression

Lasso applies an L1 penalty and can set coefficients exactly to zero, providing automatic variable selection.

#### Elastic-Net

Elastic-Net combines L1 and L2 penalties and provides a compromise between Ridge and Lasso.

Cross-validation was used to select appropriate regularization parameters.

### 3. Nonlinear Regression & Bias-Variance

A nonlinear function was simulated:

```text
f(x) = sin(2πx) + 0.5 cos(4πx) + x²
```

Polynomial regression was then used to demonstrate the effects of model complexity.

The experiments compare:

* Degree-3 polynomial regression
* Degree-10 polynomial regression
* Small dataset (`n = 10`)
* Larger dataset (`n = 200`)
* Decision-tree regression

Cross-validation was used to evaluate decision-tree complexity.

## Key Findings

### Linear Regression

OLS successfully identifies the strongest predictors in the simulated dataset. Regression diagnostics also demonstrate the importance of checking model assumptions and influential observations.

### Regularization

* **Ridge** reduces coefficient variance through continuous shrinkage.
* **Lasso** performs automatic variable selection by setting some coefficients to zero.
* **Elastic-Net** combines the benefits of both approaches and is particularly useful when predictors are correlated.

In the simulated independent-predictor setting, Lasso and Elastic-Net produce similar results.

### Bias-Variance Trade-off

* A low-degree polynomial can **underfit** a complex nonlinear relationship.
* A high-degree polynomial can **overfit** the training data and exhibit unstable behavior.
* With only `n = 10` observations, the degree-10 polynomial exhibits extreme variance.
* Increasing the sample size to `n = 200` substantially improves the behavior of the degree-10 model.
* A cross-validated decision tree provides a flexible alternative for modeling nonlinear relationships.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* SciPy
* Scikit-learn
* Statsmodels

## Project Files

```text
regression-regularization-study/
├── regression_regularization_study.ipynb
├── presentation.pptx
└── README.md
```

## Concepts Covered

Linear regression · OLS · Regression diagnostics · Ridge regression · Lasso regression · Elastic-Net · Cross-validation · Polynomial regression · Decision trees · Bias-variance trade-off · Underfitting · Overfitting · Model complexity

**Course Instructor:** **Professor Roberta Siciliano**

This repository has been expanded and organized as a professional portfolio project for educational and demonstration purposes.

# Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 👨‍💻 Author

## **Subhadip Maity**

🌐 GitHub

https://github.com/subhadip191

💼 LinkedIn

https://linkedin.com/in/subhadipmaity191

---
