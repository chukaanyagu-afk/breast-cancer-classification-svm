# breast-cancer-classification-svm
Breast cancer classification using Support Vector Machines (SVM) and scikit-learn's built-in dataset, with model evaluation.
# Breast Cancer Classification Using Support Vector Machines

## Project Overview

This project applies a Support Vector Machine (SVM) classifier to the breast cancer dataset provided by scikit-learn.

The objective is to train and evaluate a model that classifies observations into the diagnostic categories represented in the dataset.

This project is intended for machine learning education and experimentation, not clinical use.

## Problem Statement

Classification is an important machine learning task in which a model learns to distinguish between predefined categories based on input features.

This project explores how SVM can be used with structured diagnostic data and demonstrates the importance of model evaluation in a healthcare-related setting.

## Objectives

- Load and explore the breast cancer dataset.
- Prepare input features for modeling.
- Train an SVM classifier.
- Evaluate its predictive performance.
- Examine the model's errors and limitations.

## Dataset

**Dataset:** Scikit-learn Breast Cancer Wisconsin dataset.

The dataset is available through the `load_breast_cancer()` function in scikit-learn and contains numerical features derived from digitized images of fine needle aspirates of breast masses, along with diagnostic labels.

No separate dataset download is required when using the built-in scikit-learn dataset.

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas (if used)
- Matplotlib
- Seaborn
- Scikit-learn

## Algorithm: Support Vector Machine

SVM is a supervised learning algorithm that learns a decision boundary separating classes. Its performance depends on factors such as feature scaling, kernel choice, and hyperparameter settings.

## Methodology

1. Load the dataset using `load_breast_cancer()`.
2. Explore the features and target labels.
3. Split the data into training and testing sets.
4. Scale the features if appropriate.
5. Train the SVM classifier.
6. Generate predictions for the test set.
7. Evaluate the model using suitable classification metrics.

## Model Evaluation

| Metric | Result |
|---|---|
| Accuracy | [100] |
| Precision | [1.00] |
| Recall | [1.00] |
| F1-score | [1.00] 

## Key Findings

- Kernel used: [rbf].
- Best evaluation result: [100% accuracy,based on false test daata].
- Main observation:the model will perform better with actual data. Actual data wasnt used based on secrecy of patients

## How to Run the Project

1. Clone or download this repository.
2. Install the dependencies.
3. Open the Jupyter Notebook.
4. Run the notebook cells in order.

Install the commonly used dependencies with:

`pip install numpy pandas matplotlib seaborn scikit-learn jupyter`

## Limitations

The dataset represents a specific collection of observations and may not reflect all patient populations or clinical settings. Model performance on this dataset does not establish clinical safety or suitability for real-world diagnosis.

## Conclusion

This project demonstrates the use of SVM for supervised classification, with practical experience in feature preparation, model training, and evaluation using scikit-learn.

## Author

Anyagu Chuka

## Project Type

Supervised Machine Learning | Binary Classification
