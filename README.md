# Customer Purchase Prediction using Machine Learning

## Overview

This project predicts whether a customer is likely to purchase a product based on demographic information such as **Gender, Age, and Estimated Salary**. Multiple machine learning classification algorithms were trained and compared to identify the best-performing model.

The project demonstrates a complete end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and model comparison.

---

## Problem Statement

Businesses spend significant resources on marketing campaigns. Identifying customers who are more likely to purchase a product enables companies to improve campaign effectiveness, increase conversion rates, and reduce marketing costs.

This project builds predictive models to classify whether a customer will purchase a product.

---

## Dataset

**Dataset:** Social Network Ads Dataset

### Features

- Gender
- Age
- Estimated Salary

### Target Variable

- Purchased
  - 0 → Customer did not purchase
  - 1 → Customer purchased

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
- Imported dataset using Pandas.

### 2. Data Inspection
- Checked dataset shape.
- Displayed sample records.
- Verified data types.
- Checked missing values.
- Identified duplicate records.

### 3. Data Preprocessing
- Removed unnecessary columns.
- Encoded categorical variables.
- Selected relevant features.

### 4. Exploratory Data Analysis (EDA)
- Correlation Heatmap
- Distribution Analysis
- Relationship between features
- Purchase distribution

### 5. Feature Engineering
Input Features:
- Gender
- Age
- Estimated Salary

Target:
- Purchased

### 6. Train-Test Split
- Training Data: 80%
- Testing Data: 20%

### 7. Feature Scaling
Applied **StandardScaler** to normalize numerical features before training distance-based and linear models.

### 8. Model Training

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

### 9. Model Evaluation

Models were evaluated using:

- Accuracy Score
- Confusion Matrix

### 10. Model Comparison

The performance of all five models was compared to identify the most accurate classifier.

---

# Machine Learning Models

## Logistic Regression
Accuracy: **88.75%**

## Decision Tree
Accuracy: **85.00%**

## Random Forest
Accuracy: **90.00%** ✅

## K-Nearest Neighbors (KNN)
Accuracy: **82.50%**

## Support Vector Machine (SVM)
Accuracy: *(Update with your result)*

---

# Best Model

**Random Forest Classifier**

Reason:
- Highest accuracy among all tested models.
- Better prediction performance compared to other classifiers.
- Lower false negative rate than Logistic Regression.

---

## Visualizations

- Correlation Heatmap
- Confusion Matrix
- Accuracy Comparison
- Dataset Overview

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Customer-Purchase-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

## Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## Key Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Feature Scaling
- Supervised Machine Learning
- Classification
- Model Training
- Model Evaluation
- Model Comparison
- Business Problem Solving

---

## Business Value

This machine learning solution can help businesses:

- Identify potential customers
- Improve marketing campaign efficiency
- Increase customer conversion rates
- Reduce marketing costs
- Support data-driven decision making

---

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- ROC Curve Analysis
- Precision, Recall and F1 Score
- Feature Importance Visualization
- Streamlit Web Application Deployment

---

## Author

**Vanshdeep Sharma**

Engineering Student | Aspiring Data Analyst

**Skills:** Python • SQL • Machine Learning • Power BI • Excel • Tableau • Scikit-learn

---
