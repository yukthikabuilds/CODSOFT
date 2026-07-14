# Task 4 - Sales Prediction

## Objective
Build a model that predicts sales based on advertising spend across TV, Radio, and Newspaper.

## Dataset
Advertising dataset (200 rows) with TV, Radio, and Newspaper ad spend, and resulting Sales.

## Steps
1. Loaded and explored the dataset (no missing values)
2. Visualized relationships between each ad channel and Sales
3. Split data into 80% training / 20% testing sets
4. Trained a Linear Regression model
5. Evaluated performance and interpreted coefficients

## Results
- **R² Score:** 0.906
- **Key insight:** Radio spend has the highest impact per dollar (coefficient 0.101), followed by TV (0.055), while Newspaper has almost no effect (0.004) — despite TV showing the clearest visual trend.

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Google Colab
