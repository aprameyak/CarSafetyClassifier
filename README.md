# Car Safety Classifier

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white&style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white&style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white&style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-42A5F5?logo=seaborn&logoColor=white&style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white&style=for-the-badge)

## About

**Car Safety Classifier** is a machine learning project that predicts the safety level of cars using structured data from a Kaggle dataset. It applies classification models to labeled car features (buying cost, maintenance, doors, capacity, luggage boot size, and safety), producing high-accuracy predictions of car safety.

The project uses **Random Forest classifiers** and **Ordinal Encoding** for categorical variables, along with exploratory data analysis and visualization of feature importance.

## Features

- **Data Cleaning & Preparation**: Preprocessed a raw dataset containing car feature labels and categorical safety ratings
- **Ordinal Encoding**: Encoded non-numeric columns using `category_encoders.OrdinalEncoder` to preserve ordinal relationships
- **Random Forest Classifier**:
  - Achieved **94.57% accuracy** using 100 decision trees
  - Evaluated model with and without specific features to assess impact
- **Feature Importance Analysis**: Visualized contributions of each feature to model performance
- **Evaluation Metrics**: Output includes accuracy score, confusion matrix, and classification report

## Technology Stack

- **Language**: Python  
- **Data Manipulation**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Encoding**: category_encoders  
- **Modeling**: Scikit-Learn (RandomForestClassifier, train_test_split, metrics)
