# Multi-Dataset Heart Disease Prediction Project
This repository contains the implementation of various machine learning models to predict heart disease based on multiple datasets, including the Cardiovascular Dataset, Framingham Dataset and Heart Disease Dataset. The models aim to identify key risk factors contributing to heart disease and predict outcomes with high accuracy.

## Table of Contents

1. Datasets
2. Project Structure
3. Models Implemented
4. Results
5. 
6. License

### 1. Datasets
- Cardiovascular Dataset: Focuses on identifying heart conditions based on cardiovascular health metrics.
- Framingham Dataset: Derived from the Framingham Heart Study, this dataset tracks risk factors over time.
- Heart Disease Dataset: Contains patient data with attributes that contribute to the likelihood of heart disease.

### 2. Project Structure
multi-dataset-heart-disease-prediction/
  │
  ├── datasets/
  │   ├── cardio_train.csv
  │   ├── framingham.csv
  │   └── heart.csv
  │
  ├── src/
  │   ├── cardio_train_models.ipynb
  │   ├── framimgham_models.ipynb
  │   ├── heart_dataset_models.ipynb
  │   └── models_used/
  │       ├── naive_bayes.py
  │       ├── knn.py
  │       ├── decision_tree.py
  │       ├── svm.py
  │       ├── random_forest.py
  │       ├── xgboost_model.py
  │       ├── neural_network.py
  │       ├── voting_classifier.py
  │       └── stacking_classifier.py
  │
  ├── models/
  │   ├── best_cardio_dataset_model/
  │   ├── best_framingham_dataset_model/
  │   └── best_heart_dataset_model/
  │
  ├── requirements.txt
  │
  └── README.md

### 3. Models Implemented
The following machine learning models were implemented to predict heart disease:

  1. Naive Bayes
  2. K-Nearest Neighbors (KNN)
  3. Decision Tree
  4. Support Vector Machine (SVM)
  5. Random Forest
  6. XGBoost
  7. Neural Network (with multiple epochs)
  8. Voting Classifier (Ensemble)
  Stacking Classifier (Ensemble)

### 4. Results
