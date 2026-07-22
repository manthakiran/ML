# Diabetes Prediction using Machine Learning

## Overview
A supervised ML project to predict the onset of diabetes based on diagnostic measurements. 
Built using the Pima Indians Diabetes dataset from the UCI ML Repository.

## Problem Statement
Early detection of diabetes can significantly improve patient outcomes. 
This model classifies patients as diabetic or non-diabetic using health indicators.

## Dataset
- Source: Pima Dataset
- Rows: 768 | Features: 12 | Target: Outcome (False = No Diabetes, True = Diabetes)
- Features: 	num_preg,	glucose_conc,	diastolic_bp, thickness, insulin,	bmi,	diab_pred, age,	diabetes_orig, skin,	has_diabetes,	diabetes
  
## Tech Stack
- Language: Python 3.x
- Editor: Jupyter Notebook
- Packages: pandas, numpy, matplotlib, scikit-learn, imblearn
- Models: Naive Bays, Random Forest, KNN

## Project Structure
diabetes-prediction-ml/
│
├── data/               → Raw dataset (CSV)
├── notebooks/          → Data Cleaning
├── models/             → Saved model files (.pkl)
├── requirements.txt    → Python dependencies
└── README.md

## Steps Performed
1. Used pima dataset
2. loaded into jupyter Notebook
3. Cleaned the Data
4. Split data into train & test sets
5. Train the model
6. Test the model
4. Evaluation: Accuracy, Precision, Recall, F1 score

## Results
| Model               | Accuracy | F1 score | Precision | Recall |
|---------------------|----------|----------|-----------|--------|
| Naive Bayes         | 73%      | 0.74     | 0.74      | 0.74   |
| Random Forest       | 74%      | 0.74     | 0.75      | 0.74   |
| KNN                 | 70%      | 0.70     | 0.71      | 0.70   |

## How to Run
git clone [https://github.com/](https://github.com/manthakiran/ML)
cd diabetes-prediction-ml
pip install -r requirements.txt

## Author
Kiran M | B.E. AI & Data Science | [LinkedIn](www.linkedin.com/in/kiran-m08)
