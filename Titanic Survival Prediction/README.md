# Task 1 - Titanic Survival Prediction

## Objective
Build a machine learning model to predict whether a passenger on the Titanic survived, based on features like age, sex, ticket class, and fare.

## Dataset
Titanic dataset from Kaggle (train.csv) - 891 passengers with features including Age, Sex, Pclass, Fare, SibSp, Parch, and Embarked.

## Steps
1. Loaded and explored the dataset
2. Handled missing values (filled Age with median, Embarked with mode, dropped Cabin)
3. Encoded categorical variables (Sex, Embarked) into numeric form
4. Split data into 80% training / 20% testing sets
5. Trained a Random Forest Classifier
6. Evaluated model performance

## Results
- **Accuracy:** 80%
- Top predictive features: Fare, Sex, and Age

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib, Google Colab
