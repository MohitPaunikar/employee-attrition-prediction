# employee-attrition-prediction
“Employee attrition analysis and machine learning using Python.”
# Employee Attrition Prediction Using Python

## Project Overview
This project uses Python and machine learning to analyze employee attrition patterns and compare classification models using an HR analytics dataset.

## Objectives
- Explore employee data and understand attrition distribution.
- Clean and preprocess data for machine learning.
- Train and compare classification models.
- Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.
- Interpret results and discuss project limitations.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure
- `notebooks/` — EDA, preprocessing, and model evaluation.
- `reports/` — Four weekly project reports.
- `data/` — Local dataset folder; the raw CSV is not included in this repository by default.

## Models Compared
- Dummy Classifier
- Logistic Regression
- Random Forest Classifier

## Key Results
The dataset contains 1,470 employee records. Of these, 237 (16.12%) are labelled as attrition and 1,233 (83.88%) as no attrition.

Logistic Regression achieved an F1-score of 0.451 and recall of 0.638 for the attrition class on the test set.

## Limitations
This is an educational project using a sample HR analytics dataset. The results do not establish causation and should not be used to make automated employment decisions.

## Author
Mohit Paunikar
