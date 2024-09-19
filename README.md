# Breast-Cancer-Classification-using-SVM-
This project focuses on classifying breast cancer data into **malignant** and **benign** tumors using the **Support Vector Machine (SVM)** algorithm. The project includes data preprocessing, feature scaling, model training, evaluation, and visualizations to provide insights into the dataset and model performance.

## Overview

Breast cancer is a common type of cancer that requires accurate diagnosis to improve patient outcomes. This project leverages machine learning techniques to build a model that assists in the classification of breast cancer tumors using a widely known dataset.

## Requirements
- **Python 3.6+**
- **scikit-learn**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**

## Dataset

The dataset used in this project is the **Breast Cancer Wisconsin (Diagnostic) Dataset**, available in the `sklearn.datasets` module. It consists of 569 samples of breast cancer tissue, with each sample having 30 numerical features.
- **Malignant (Class 0)**: Cancerous tumors
- **Benign (Class 1)**: Non-cancerous tumors

You can read more about the dataset [here](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html).

## Data Preprocessing

Several preprocessing steps are applied to the dataset to prepare it for machine learning:

- **Feature Scaling**: All 30 features are scaled using **StandardScaler** to ensure they have similar ranges and avoid biases.
- **Train-Test Split**: The dataset is split into 80% training data and 20% testing data to evaluate the model's performance.

  
## Modeling

The model used for classification is a **Support Vector Machine (SVM)** with a linear kernel. SVM is a powerful algorithm that works well for binary classification problems such as this one.

Key steps:
- The model is trained on the training set.
- Predictions are made on the test set.
- Evaluation metrics are calculated to measure performance.

## Evaluation

The model's performance is evaluated using the following metrics:

- **Accuracy**: Overall accuracy of the classification.
- **Confusion Matrix**: Breaks down true positives, false positives, true negatives, and false negatives.
- **Classification Report**: Provides detailed metrics like precision, recall, and F1-score.

## Visualizations

Various visualizations are included to understand the dataset and the model's predictions.

## License

This project is licensed by the author. All rights reserved by Heriz Oumaima.
