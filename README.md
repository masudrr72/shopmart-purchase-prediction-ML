# ShopSmart Purchase Prediction (Machine Learning Project)

This project was completed as part of my Machine Learning learning journey with Apna College.

## Problem Statement

The goal of this project is to build a machine learning model that predicts whether an e-commerce visitor will make a purchase based on their browsing session behavior.

The dataset contains 12,330 user sessions with a mix of numerical and categorical features.

Because the dataset is imbalanced, the main evaluation metric used for the model is the **F1 Score**.

## Objective

Act as an ML Engineer to:

- Perform Exploratory Data Analysis (EDA)
- Preprocess numerical and categorical features
- Train a Decision Tree classifier
- Apply pruning to control overfitting
- Evaluate the model performance

The project required achieving a minimum **F1 Score of 0.55**.

## Model Used

Decision Tree Classifier

## Results

### Train Performance
Accuracy: **0.912**  
F1 Score: **0.690**

### Test Performance
Accuracy: **0.897**  
F1 Score: **0.661**

The model successfully exceeded the required benchmark F1 score.

## Evaluation Metrics

Classification Report:

Precision | Recall | F1-score

Class 0: 0.92 | 0.95 | 0.94  
Class 1: 0.73 | 0.61 | 0.66

Overall Accuracy: **0.90**

## Key Learnings

- Handling imbalanced datasets
- Feature preprocessing
- Decision Tree model training
- Model evaluation using F1 Score
- Understanding real-world ML workflow

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
