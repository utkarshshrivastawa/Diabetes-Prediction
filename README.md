# Diabetes-Prediction Using Support Vector Machine

## Project Objective: 
To accurately predict whether a patient has diabetes based on diagnostic measurements.

## Dataset Overview:

1. Source: The dataset is loaded from a CSV file containing diagnostic measurements.
2. Shape: Consists of 768 observations with 9 features each.
3. Features: Include Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, and Outcome (where Outcome is the target variable indicating 0 for non-diabetic and 1 for diabetic cases).
4. Null Values: The dataset contains no missing values.

## Data Preprocessing:

1. Standardization: Feature scaling was performed using StandardScaler to normalize the dataset.

## Modeling:

1. Algorithm: Support Vector Machine (SVM) with a linear kernel.
2. Training: The model was trained using 80% of the dataset.
3. Evaluation: The performance was evaluated on both training and testing sets.

## Performance Metrics:

1. Training Data Accuracy: 78.66%
2. Testing Data Accuracy: 77.27%

## Predictive System: 

Demonstrated the prediction process using an example input, showing how to preprocess and predict outcomes for individual cases.

## Contributions:

1. Encourages contributions such as issue reporting or suggestions for improvements.
2. Offers a detailed guide for setting up the environment, running the code, and contributing to the project.
