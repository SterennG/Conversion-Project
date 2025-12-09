# Conversion Rate Challenge

## Overview
This project is a machine learning competition aimed at predicting the conversion rate of the website *www.datascienceweekly.org*. The goal is to predict whether a user will subscribe to the newsletter based on their behavior and demographic data.

## Objectives
1. **Prediction**: Build a machine learning model to predict conversions (Target $Y$) on a test set.
2. **Performance**: Maximize the F1-score.
3. **Analysis**: Interpret model parameters to provide actionable recommendations to increase subscriptions.

## Dataset
- `data_train.csv`: Labeled data ($X$ and $Y$) used for EDA, training, and evaluation.
- `data_test.csv`: Unlabeled data ($X$ only) used for the final submission to the leaderboard.

## Workflow
1. **EDA & Preprocessing**: Data visualization, cleaning, and feature engineering.
2. **Modeling**: Training various models (Baseline, Logistic Regression, Decision Trees, etc.).
3. **Optimization**: Hyperparameter tuning (GridSearch) and feature selection to improve the F1-score.
4. **Submission**: Generating predictions on data_test.csv.
5. **Recommendations**: Identifying key features influencing the conversion rate.

## Tech Stack
- Python (Jupyter Notebook)
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.