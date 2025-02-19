# Codealpha_project_Titanic-_predictions
rediction Project
markdown
Copy
Edit
# Titanic Survival Prediction using Machine Learning

## Project Overview
This project uses machine learning to predict the survival of passengers aboard the Titanic based on various features like **age**, **sex**, **ticket class**, and more. The model was built using a **Random Forest Classifier**, with data preprocessing, feature engineering, and hyperparameter tuning applied to improve prediction accuracy.

## Key Features
- **Data Collection**: Titanic dataset with **891 training** entries and **418 test entries**.
- **Data Preprocessing**:
  - Missing values were imputed.
  - Categorical variables were encoded.
  - Numerical features were scaled.
- **Exploratory Data Analysis (EDA)**:
  - Visualizations of feature distributions and correlations.
  - Analysis of survival rates by class and gender.
- **Machine Learning Model**: Random Forest Classifier was trained and tuned using **Grid Search** for hyperparameter optimization.
- **Model Accuracy**: Achieved an accuracy of **95.5%**.
Steps to Run
Data Preprocessing: Handle missing values, encode categorical variables, and scale numerical features.

EDA: Visualize key patterns in the data, like survival rates by class and gender.

Model Training: Train a Random Forest Classifier using Stratified Shuffle Split and Grid Search for hyperparameter optimization.

Evaluation: Evaluate the model's performance on test data and make predictions.

Results

The model predicts whether a passenger survived based on various features with an accuracy of 95.5%.

Conclusion

This project demonstrates the use of machine learning for predicting survival on the Titanic. The Random Forest model is effective in classifying passenger survival with high accuracy.
