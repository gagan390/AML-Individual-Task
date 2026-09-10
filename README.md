# Diabetes Prediction Using Machine Learning

## Project Overview

This project focuses on predicting whether a person is likely to have diabetes using machine learning classification algorithms. The system analyzes patient health-related information and identifies patterns that can be used to classify patients as diabetic or non-diabetic.

The project demonstrates a complete machine learning workflow, including data loading, data preprocessing, feature preparation, model training, prediction, and performance evaluation.

## Objective

The main objectives of this project are:

- To analyze a diabetes dataset containing patient health information.
- To preprocess and prepare the dataset for machine learning.
- To implement classification algorithms for diabetes prediction.
- To compare the performance of different machine learning models.
- To evaluate the models using suitable classification metrics.
- To identify the best-performing model.

## Dataset

The dataset contains health-related attributes of patients that are used to predict diabetes.

### Features

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

### Target Variable

The target variable is `Outcome`.

- `0` – Non-Diabetic
- `1` – Diabetic

## Machine Learning Algorithms

The following classification algorithms are implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Naive Bayes

### Logistic Regression

Logistic Regression is used for binary classification. It predicts the probability of a patient belonging to the diabetic or non-diabetic class.

### Decision Tree

Decision Tree classifies patients using a sequence of feature-based decisions. It provides an easy-to-understand tree structure for the prediction process.

### Naive Bayes

Naive Bayes is a probability-based classification algorithm that uses Bayes' theorem to determine the most likely class for a patient.

## Methodology

The project follows these steps:

1. Load the diabetes dataset.
2. Explore and understand the dataset.
3. Perform data preprocessing.
4. Separate input features and target variable.
5. Split the dataset into training and testing data.
6. Train Logistic Regression, Decision Tree, and Naive Bayes models.
7. Generate predictions using the test data.
8. Evaluate model performance.
9. Compare the models.
10. Select the best-performing model.

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics provide a detailed understanding of the classification performance of each model.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Structure

```text
diabetes_prediction_aml_classification_final/
│
├── diabetes_prediction_aml_classification_final.ipynb
├── README.md
└── dataset/
    └── diabetes.csv
