# Heart Disease Prediction Model

## Overview
This project aims to develop a machine learning model that predicts the presence of heart disease based on various health indicators using the Random Forest algorithm. The model processes patient data to assist in early diagnosis, ultimately improving patient outcomes.

## Features
- Data preprocessing (encoding categorical variables, scaling)
- Random Forest Classifier for prediction
- Model evaluation using accuracy, precision, recall, and confusion matrix
- Model persistence with joblib for future predictions

## Dataset
The dataset used is the **Heart Disease UCI** dataset, which contains health attributes and outcomes related to heart disease. You can find the dataset [here](https://archive.ics.uci.edu/ml/datasets/heart+Disease).

## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- Joblib
- NumPy
- Seaborn
- Matplotlib

## Installation
Clone the repository and install the required packages:
```bash
git clone <repository_url>
cd heart-disease-prediction
pip install -r requirements.txt
