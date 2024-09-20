# Multi-Dataset Heart Disease Prediction Project
This repository contains the implementation of various machine learning models to predict heart disease based on multiple datasets, including the Cardiovascular Dataset, Framingham Dataset and Heart Disease Dataset. The models aim to identify key risk factors contributing to heart disease and predict outcomes with high accuracy.

## Table of Contents

1. Datasets
2. Project Structure
3. Models Implemented
4. Results 
5. License
6. Acknowledgements

### 1. Datasets
- Cardiovascular Dataset: Focuses on identifying heart conditions based on cardiovascular health metrics.
- Framingham Dataset: Derived from the Framingham Heart Study, this dataset tracks risk factors over time.
- Heart Disease Dataset: Contains patient data with attributes that contribute to the likelihood of heart disease.

### 2. Project Structure
multi-dataset-heart-disease-prediction/
├── src/                        
│   ├── cardio_train_models.ipynb            
│   ├── framimgham_models.ipynb                  
│   ├── heart_dataset_models.ipynb             
│   └── models_used/
│       ├── naive_bayes.py                    
│       ├── k_nearest_neighbor.py 
│       ├── decision_tree.py                    
│       ├── support_vector_machine.py                    
│       ├── random_forest.py         
│       ├── xgboost.py                
│       ├── neural_network.py        
│       ├── voting_classifier.py  
│       └── stacking_classifier.py
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
  9. Stacking Classifier (Ensemble)

### 4. Results

  | Dataset                 | Best Model             | Accuracy |
  |-------------------------|------------------------|----------|
  | Heart Dataset           | Voting Classifier      | 87%      |
  | Heart Dataset           | Random Forest          | 86%      |
  | Framingham Dataset      | Neural Network         | 85%      |
  | Framingham Dataset      | Support Vector Machine | 84%      |
  | Cardiovascular Dataset  | XG Boost               | 73%      |
  | Cardiovascular Dataset  | Neural Network         | 74%      |
  | Cardiovascular Dataset  | Stacking Classifier    | 73%      |

  After training, the best-performing models for each dataset are:

  - Cardiovascular Dataset: Stacking Classifier with Gradient Boosting and Neural Network as base models.
  - Framingham Dataset: Neural Network and SVM.
  - Heart Dataset: Voting Classifier (combining Random Forest, Gradient Boosting, and SVM).

### 5. License
  This project is licensed under the MIT License.

### 6. Acknowledgements
We would like to acknowledge the providers of the datasets used in this project:
  - Kaggle for providing the Heart Disease dataset
  - Framingham Heart Study for the Framingham dataset
  - Kaggle for providing Cardiovascular disease dataset
  - Creators and maintainers of the Cleveland, Hungarian, Switzerland, and Long Beach VA heart disease dataset and all contributors and researchers in the field of heart disease predictio
