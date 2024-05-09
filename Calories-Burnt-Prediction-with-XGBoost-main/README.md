# Project Description: Calorie Prediction with XGBoost

## Overview
This project utilizes machine learning to predict calorie consumption based on user characteristics and exercise data. It employs the XGBoost regression algorithm, known for its efficiency in handling numerical predictions.

## Steps

- **Data Integration:**
  - Combines two datasets, `calories.csv` and `exercise.csv`, into a single DataFrame (`calories_data`).

- **Exploratory Data Analysis (EDA):**
  - Visualizes gender distribution, explores age, height, and weight distributions.
  - Computes descriptive statistics and analyzes feature correlations.

- **Data Preprocessing:**
  - Encodes gender (male: 0, female: 1).

- **Feature Engineering:**
  - Separates features (X) and target variable (Y).

- **Data Splitting:**
  - Divides the dataset into training and test sets.

- **Model Training:**
  - Utilizes XGBoost Regressor to learn patterns from the training data.

- **Evaluation:**
  - Assesses model performance on the test set using Mean Absolute Error (MAE).
    
- **User Input:**
  - Collects gender, age, height, weight, exercise duration, heart rate, and body temperature.

- **Prediction Display:**
  - Predicts and displays the calories burnt based on user input.

## Conclusion
This project demonstrates the application of machine learning in predicting calorie consumption, providing valuable insights into user behavior and exercise patterns. The XGBoost model is evaluated for accuracy through the MAE metric, offering a practical solution for predicting and understanding calorie expenditure.
