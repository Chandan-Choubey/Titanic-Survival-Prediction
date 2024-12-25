# Titanic Survival Prediction

## Overview
This project aims to predict whether a passenger survived the Titanic disaster using a machine learning model trained on the Titanic dataset. The dataset includes features such as passenger age, gender, ticket class, and fare, which are used to build the predictive model.

## Approach

### 1. Data Preprocessing
- **Feature Selection:** Chose relevant features (`Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`).
- **Handling Missing Values:** Imputed missing values in the `Age` column with the mean and filled missing values in the `Embarked` column with the mode.
- **Encoding Categorical Variables:** Encoded `Sex` and `Embarked` using label encoding.
- **Feature Scaling:** Applied standard scaling to normalize numerical features.

### 2. Model Training
- Used a **Random Forest Classifier** for its robustness and high accuracy.
- Split the data into 80% training and 20% testing sets.
- Tuned hyperparameters and evaluated the model using metrics like accuracy, precision, recall, and F1-score.

### 3. Evaluation
- Achieved an accuracy of ~85% on the test set.
- Evaluated the model's performance using a confusion matrix and classification report.

## Results
The Random Forest model effectively predicts survival with high accuracy. Further improvements can be made by experimenting with other models, performing hyperparameter tuning, and engineering additional features.

## Challenges
- Imputing missing values in `Age` required careful consideration.
- Balancing feature selection and model complexity was crucial to avoid overfitting.


