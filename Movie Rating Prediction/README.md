# Task 2 - Movie Rating Prediction

## Objective
Build a model that predicts a movie's IMDb rating based on features like genre, director, actors, year, and votes.

## Dataset
IMDb Movies India dataset (7,919 cleaned rows after removing entries with no rating).

## Steps
1. Loaded and explored the dataset
2. Dropped rows with missing Rating (target variable)
3. Dropped Duration column (too many missing values)
4. Cleaned Year and Votes columns into proper numeric formats
5. Frequency-encoded Genre, Director, and Actor columns (converted names into counts of appearances)
6. Split data into 80% training / 20% testing sets
7. Trained a Random Forest Regressor
8. Evaluated performance and feature importance

## Results
- **R² Score:** 0.35
- **Mean Squared Error:** 1.21
- **Key insight:** Votes and Year were the strongest predictors, more influential than director, actor, or genre. The moderate R² reflects that movie ratings depend on many real-world factors (writing quality, marketing, audience sentiment) not captured in this dataset.

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib, Google Colab
