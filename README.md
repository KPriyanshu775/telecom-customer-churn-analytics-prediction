# Telecom Customer Churn Analytics and Prediction

## Project Overview

This project is an end-to-end data science capstone developed as part of the Yuva Intern Virtual Data Science with Python internship.

The objective is to analyze telecom customer behaviour, identify customer segments and predict customers who may be at risk of leaving the company.

The project uses the IBM Telco Customer Churn dataset and combines exploratory data analysis, unsupervised machine learning and supervised machine learning.

## Dataset

- Source: IBM Telco Customer Churn
- Total customers: 7,043
- Original features: 21
- Target variable: Churn
- Churn categories: Yes and No

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- Git and GitHub

## Project Workflow

1. Data acquisition and inspection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Customer segmentation using K-Means clustering
5. Churn prediction using Logistic Regression and Random Forest
6. Model evaluation and comparison
7. Feature importance analysis
8. Customer churn risk analysis
9. Business recommendations and project documentation

## Model Results

### Customer Segmentation

- Algorithm: K-Means
- Selected clusters: 6
- Silhouette score: 0.4724

### Churn Prediction

Logistic Regression:
- Test accuracy: 73.81%
- Precision: 50.43%
- Recall: 78.34%
- F1-score: 61.36%
- ROC-AUC: 0.8416

Random Forest:
- Test accuracy: 76.15%
- Precision: 53.85%
- Recall: 71.12%
- F1-score: 61.29%
- ROC-AUC: 0.8348

Logistic Regression was selected based on its higher cross-validation ROC-AUC.

## Project Structure

- `data/raw/` – Original dataset
- `data/processed/` – Cleaned dataset and customer segments
- `notebooks/` – Complete Jupyter Notebook implementation
- `outputs/` – Prediction results, evaluation reports and analysis
- `outputs/figures/` – Data visualizations and model evaluation graphs
- `models/` – Saved trained model
- `reports/` – Final project report and business insights

## Key Business Insights

The analysis examines customer churn across contract types, payment methods, internet services and customer tenure.

The results can help a telecom business identify customer groups requiring retention attention and develop targeted customer retention strategies.

## Conclusion

This capstone demonstrates a complete data science workflow, from raw data acquisition and preprocessing to machine learning model development, evaluation and business recommendations.

The project was developed as the final capstone assignment of the six-week Yuva Intern Virtual Data Science with Python internship.