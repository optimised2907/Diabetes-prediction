# Diabetes Prediction Model

![Python Version](https://img.shields.io/badge/Python-3.9%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-brightgreen)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview
This project implements a machine learning pipeline to predict diabetes based on health diagnostic metrics. Using the classic Pima Indians Diabetes dataset, it covers the full workflow from data preprocessing and exploratory analysis to model training and evaluation. The Jupyter notebook demonstrates various classification algorithms and their performance metrics.

## Dataset
**Pima Indians Diabetes Dataset**  
- 768 patient records with 9 medical features:
  1. Pregnancies
  2. Glucose
  3. BloodPressure
  4. SkinThickness
  5. Insulin
  6. BMI
  7. DiabetesPedigreeFunction
  8. Age
  9. Outcome (target: 0=no diabetes, 1=diabetes)

[Download dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## Key Features
- **Data Preprocessing**: Handles missing values by imputation with statistical measures
- **Exploratory Analysis**: Includes correlation matrices and feature distribution visualizations
- **Multiple Models**: Compares 7 classification algorithms
- **Evaluation Metrics**: Accuracy, precision, recall, F1-score, and confusion matrices


## Prerequisites
- Python 3.7+
- pip package manager
