# Employee Attrition Prediction Using Python

A Python-based machine learning project to explore employee attrition patterns, preprocess HR data, and compare classification models.

## Project Overview
This project uses the IBM HR Analytics Employee Attrition dataset to analyze employee attrition and evaluate machine learning models for classifying attrition.

## Objectives
- Explore employee data and understand attrition distribution.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA) and visualization.
- Train and compare classification models.
- Evaluate model performance using accuracy, precision, recall, F1-score, and ROC-AUC.
- Interpret findings and discuss model limitations.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure
- `notebooks/01_exploratory_data_analysis.ipynb` — Exploratory data analysis and visualizations.
- `notebooks/02_data_preprocessing.ipynb` — Data cleaning and preprocessing.
- `notebooks/03_model_training_evaluation.ipynb` — Model training and evaluation.
- `reports/` — Four weekly project reports.
- `data/` — Local dataset folder; the raw CSV is not included by default.

## Dataset Summary
- Total records: 1,470
- Attrition: 237 employees (16.12%)
- No attrition: 1,233 employees (83.88%)

The dataset contains an imbalanced target variable, making recall, precision, and F1-score important evaluation metrics alongside accuracy.

## Models Compared
- Dummy Classifier (baseline)
- Logistic Regression
- Random Forest Classifier

## Model Evaluation Results

| Model | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 0.752 | 0.349 | 0.638 | 0.451 | 0.803 |
| Random Forest | 0.840 | 0.500 | 0.170 | 0.254 | 0.798 |
| Dummy Classifier | 0.840 | 0.000 | 0.000 | 0.000 | 0.500 |

Logistic Regression achieved a higher recall and F1-score for the attrition class, while Random Forest achieved higher accuracy but lower recall. The Dummy Classifier illustrates why accuracy alone can be misleading for an imbalanced dataset.

## Limitations
This is an educational project using a sample HR analytics dataset. The results do not establish causation and should not be used as the sole basis for employment decisions or automated decisions about employees.

## Author
Mohit Paunikar
