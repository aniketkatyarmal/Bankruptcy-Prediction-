# Bankruptcy-Prediction-
Overview:-

This project focuses on predicting company bankruptcy using various machine learning models. Accurate bankruptcy prediction is crucial for stakeholders like financial institutions, investors, and policymakers to mitigate financial risks and enhance system stability. The project involves developing, evaluating, and comparing multiple machine learning models to determine the best approach for accurate predictions.

Problem Statement:-

Bankruptcy prediction is challenging due to the complexity and variability of financial data. The objective of this project is to develop and evaluate predictive models such as Logistic Regression, Random Forest, Gradient Boosting, Support Vector Machine (SVM), and Decision Trees. The goal is to select the best-performing model based on accuracy, precision, recall, F1-score, and AUC for deployment in real-world scenarios.

Data Overview:-

Initial Dataset Size: 250 companies, each with 7 features.
Post-Preprocessing Size: 103 samples (after removing 147 duplicate entries).

Features::-

Industrial Risk
Management Risk
Financial Flexibility
Credibility
Competitiveness
Operating Risk
Target Variable Class (Bankrupt/Not Bankrupt):-

Data Preprocessing
Checked for null values.
Identified and removed duplicate entries.
Summarized data statistics.
Modeling Approach
Models Implemented:
Logistic Regression
Decision Trees
Random Forest
Gradient Boosting
SVM
Steps:-

Encoded the target variable.
Split the dataset into training and testing sets.
Applied SMOTE to balance the target variables.
Standardized the data using a standard scaler.
Implemented and compared multiple models.
Model Evaluation:-

Classification reports, ROC curves, and confusion matrices were used to compare model performance.
Feature importance and learning curves were analyzed.
Hyperparameter tuning was performed using GridSearchCV and RandomizedSearchCV.
Results
The models were evaluated based on their performance metrics, and the best-performing model was selected for potential deployment. The results provide a comprehensive analysis of the strengths and weaknesses of each model.

Conclusion:-
This project demonstrates the importance of accurate bankruptcy prediction and the effectiveness of different machine learning models in tackling this challenge. The selected model(s) can be used for real-world applications to enhance financial decision-making processes.
