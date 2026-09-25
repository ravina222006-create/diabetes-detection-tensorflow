# Diabetes Detection Binary Classifier using TensorFlow

## Project Overview
This project implements a binary classification model using TensorFlow to predict whether a patient has diabetes or not.

## Dataset
Pima Indians Diabetes Dataset.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Google Colab

## Models

### Model 1 – Without Hidden Layer
Input Layer → Output Layer

Test Accuracy: 70%

### Model 2 – With Hidden Layer and Dropout
Input Layer → Hidden Layer (16 neurons) → Dropout (0.3) → Output Layer

Test Accuracy: 62%

## Steps Performed
1. Loaded the diabetes dataset.
2. Checked missing values.
3. Separated input features and target variable.
4. Split data into training and testing sets.
5. Applied feature scaling.
6. Built and trained two TensorFlow models.
7. Evaluated both models using test accuracy.
8. Generated diabetes predictions.

## Conclusion
Two TensorFlow-based binary classification models were developed for diabetes prediction. The models were trained and evaluated using the Pima Indians Diabetes Dataset.
