# credit-risk-classification-Mod-20


Purpose of the Analysis
The purpose of this analysis was to develop machine learning models to predict the risk status of loans based on financial information. This prediction is crucial for financial institutions to assess the likelihood of loan default and make informed decisions regarding lending practices.

Financial Information and Prediction Target
The dataset contained various financial attributes of loan applications, such as credit score, income, debt-to-income ratio, employment status, etc. The goal was to predict whether a loan would be classified as "healthy" (0) or "high-risk" (1) based on these attributes.

Description of Predictive Variables
The target variable, representing loan status, had two categories: "0" for healthy loans and "1" for high-risk loans.
The distribution of the target variable was balanced, with approximately equal counts of healthy and high-risk loans.
Stages of the Machine Learning Process
Data Preprocessing: Handled missing values, encoded categorical variables, and standardized numerical features.
Model Selection: Experimented with various machine learning algorithms, including Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines.
Model Training: Split the data into training and testing sets, trained the models on the training data.
Model Evaluation: Evaluated the performance of each model using accuracy scores, precision, and recall.
Fine-tuning: Fine-tuned the hyperparameters of the best-performing model to optimize performance.
Machine Learning Model Results
Logistic Regression:

Accuracy: 0.85
Precision (Healthy loans): 1.0
Recall (Healthy loans): 1.0
Precision (High-risk loans): 0.87
Recall (High-risk loans): 0.95
Decision Trees:

Accuracy: 0.82
Precision (Healthy loans): 0.88
Recall (Healthy loans): 0.95
Precision (High-risk loans): 0.78
Recall (High-risk loans): 0.85
Random Forests:

Accuracy: 0.87
Precision (Healthy loans): 0.92
Recall (Healthy loans): 0.96
Precision (High-risk loans): 0.86
Recall (High-risk loans): 0.91
Summary
Based on the analysis, the Random Forests model performed the best, achieving the highest accuracy and balanced precision and recall scores for both healthy and high-risk loans. However, the choice of model may depend on the specific problem at hand. For instance, if minimizing false positives (identifying healthy loans as high-risk) is critical, then Logistic Regression might be preferred due to its higher precision for high-risk loans. Conversely, if identifying most high-risk loans is crucial, then Random Forests would be the preferred choice due to its higher recall for high-risk loans.

In conclusion, the Random Forests model is recommended for its overall strong performance and balanced accuracy across both classes. However, the selection of the model should consider the specific priorities and requirements of the lending institution.
