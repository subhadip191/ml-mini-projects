# Student Academic Outcome Analysis

An exploratory data analysis and unsupervised learning study of student academic outcomes using demographic, academic, and socioeconomic data.

## Overview

This project analyzes a dataset of **4,424 students** with **36 features** describing academic performance, demographic characteristics, and socioeconomic conditions. The objective is to understand the factors associated with three student outcomes:

* **Dropout**
* **Enrolled**
* **Graduate**

The analysis combines exploratory data analysis, correlation analysis, Principal Component Analysis (PCA), and K-Means clustering to identify important patterns within the dataset.

## Objectives

* Explore the structure and distribution of the dataset.
* Investigate relationships between academic and socioeconomic variables.
* Identify the factors most strongly associated with student outcomes.
* Reduce dimensionality using PCA.
* Discover groups of students using K-Means clustering.
* Interpret the relationship between academic performance and student outcomes.

## Methodology

### 1. Data Loading & Cleaning

The dataset was inspected for missing values, variable types, and basic statistical properties.

The dataset contains no missing values, and categorical information is primarily encoded using binary numerical variables.

### 2. Exploratory Data Analysis

The analysis includes:

* Univariate distributions
* Summary statistics
* Correlation analysis
* Scatterplots
* Contingency tables
* Comparison of academic and socioeconomic characteristics across outcome groups

### 3. Principal Component Analysis

PCA was applied after feature standardization to reduce the dimensionality of the dataset and identify the dominant sources of variation.

The first principal components capture substantial variation related primarily to:

* Academic performance
* Curricular unit completion
* Grades
* Financial status

### 4. K-Means Clustering

K-Means clustering was used to identify groups of students with similar characteristics.

The number of clusters was selected using the **elbow method**, resulting in **k = 3**.

## Key Findings

* Academic performance is strongly associated with student outcomes.
* First- and second-semester academic performance show strong positive relationships.
* Students with very low or zero completed curricular units are heavily concentrated in the **Dropout** group.
* Tuition-fee status and debtor status show strong relationships with student outcomes.
* PCA reveals a major separation between students with stronger and weaker academic performance.
* K-Means clustering partially reproduces the structure of the known outcome groups, while **Enrolled** students tend to occupy an intermediate position.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Note

This project focuses on **exploratory and unsupervised analysis** rather than building a supervised prediction model.

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

