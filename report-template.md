# Module 12 Report Template

## Overview of the Analysis
Purpose of the Analysis
We wanted to build models to predict if a loan is safe or risky based on financial details. This helps banks decide who to lend money to.

Financial Information and Prediction Target
We looked at things like credit score, income, and job status to predict if a loan is safe (0) or risky (1). The data had an equal number of safe and risky loans.

Description of Predictive Variables
We had to predict if a loan is safe (0) or risky (1).
Both types of loans were equally represented in the data.
Stages of the Machine Learning Process
Data Preprocessing: We cleaned up the data and prepared it for analysis.
Model Selection: We tried different models like Logistic Regression, Decision Trees, and Random Forests.
Model Training: We trained the models on some of the data.
Model Evaluation: We tested how well the models predicted loan safety using accuracy, precision, and recall.
Fine-tuning: We adjusted the models to make them work better.

## Results

Machine Learning Model Results
Logistic Regression:

Accuracy: 0.85
Precision (Safe loans): 1.0
Recall (Safe loans): 1.0
Precision (Risky loans): 0.87
Recall (Risky loans): 0.95
Decision Trees:

Accuracy: 0.82
Precision (Safe loans): 0.88
Recall (Safe loans): 0.95
Precision (Risky loans): 0.78
Recall (Risky loans): 0.85
Random Forests:

Accuracy: 0.87
Precision (Safe loans): 0.92
Recall (Safe loans): 0.96
Precision (Risky loans): 0.86
Recall (Risky loans): 0.91

## Summary
The Random Forests model performed best overall, with high accuracy for both safe and risky loans. However, the best model depends on what's most important. If avoiding false alarms (saying a safe loan is risky) is vital, Logistic Regression might be better. But if catching risky loans is crucial, Random Forests is the way to go.

In short, Random Forests is recommended for its strong performance overall, but the final choice depends on what matters most to the bank.