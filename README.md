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
Heart-Disease-Prediction/
├── src/                        
│   ├── naive_bayes.py            
│   ├── knn.py                  
│   ├── decision_tree.py         
│   ├── svm.py                    
│   ├── random_forest.py         
│   ├── xgboost.py                
│   ├── neural_network.py        
│   ├── voting_classifier.py      
│   └── stacking_classifier.py    
├── models/                      
│   ├── best_cardio_dataset_model.ipynb    
│   ├── best_framingham_dataset_model.ipynb      
│   └── best_heart_dataset_model.ipynb          
├── datasets/                     
│   ├── cardio_train.csv      
│   ├── heart.csv                 
│   └── framingham.csv           
├── README.md                     
├── requirements.txt              
└── LICENSE                       


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
