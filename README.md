# Chronic-Disease-Prediction-Using-Machine-Learning
Chronic Disease Prediction Using Machine Learning

A unified machine learning framework designed for the early prediction and diagnosis of major chronic illnesses: Diabetes, Breast Cancer, and Heart Disease. This project leverages supervised learning algorithms and extensive data preprocessing techniques to achieve high diagnostic accuracy, aiding in clinical decision support and personalized medicine.

- Overview

The growing availability of electronic health records (EHR) makes data-driven decision-making in healthcare highly effective. This project presents a robust pipeline for predicting multiple chronic diseases. By emphasizing model interpretability and clinical relevance, the system aims to alert clinicians to high-risk patients, facilitating early detection and reducing the burden on healthcare systems.

- Key Features

Multi-Disease Prediction: A generalized pipeline capable of predicting three different chronic diseases.

Robust Preprocessing: Implements Local Outlier Factor (LOF) for outlier detection and removal, alongside RobustScaler and StandardScaler for optimal feature scaling.

Hyperparameter Tuning: Utilizes GridSearchCV to fine-tune models and prevent overfitting.

Comprehensive Evaluation: Evaluates models using Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC scores.

- Datasets Used

The models were trained and evaluated on three publicly available benchmark clinical datasets (sourced from UCI Machine Learning Repository & Kaggle):

PIMA Indian Diabetes Dataset: 768 samples with 8 diagnostic attributes for predicting the presence of diabetes.

UCI Breast Cancer Wisconsin Dataset: 569 samples with 30 numeric features representing cell nuclei characteristics.

Cleveland Heart Disease Dataset: 303 records with 13 relevant clinical attributes.

- Machine Learning Models

Several classifiers were tested and compared across the datasets to find the most consistent and accurate results:

Support Vector Machines (SVM)

Logistic Regression (LR)

Random Forest (RF)

K-Nearest Neighbors (KNN)

Decision Trees

- Performance & Results

The applied models demonstrated superior classification capabilities, particularly SVM and Logistic Regression, which proved highly effective across the disease models:

Diabetes Prediction: Achieved 88% Accuracy using Support Vector Machines (SVM).

Breast Cancer Prediction: Achieved 98% Accuracy using SVM and 96% Accuracy using Logistic Regression.

Heart Disease Prediction: Achieved 82% Accuracy using Logistic Regression.

- Tech Stack

Language: Python

Machine Learning: Scikit-Learn

Data Processing & Analysis: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

- Authors & Researchers

This project is based on the research conducted at Vishwakarma Institute of Technology (VIT), Pune.

Sanket Auti

Omkar Bankar

Prathamesh Bhosale

Developed for the early detection and prevention of chronic illnesses, paving the way for data-driven, personalized medicine.
