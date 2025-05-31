# Credit-Score-Classification-Project
The project aims to predict an individual's credit score (High, Average, or Low) based on financial features such as age, gender, income, education, marital status, number of children, and home ownership.

The goal of this project is to build a machine learning model that accurately classifies credit scores into three categories: High, Average, and Low. The dataset used contains 164 entries with 8 features, and the project evaluates three classification algorithms—Random Forest, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM)—to determine the best-performing model.

# Steps

Introduction: Outlines the goal to classify credit scores with a financial context.

Library Imports: Loads tools for data handling and modeling.

Load Dataset: Imports a 164-entry CSV with 8 features (e.g., Age, Income, Credit Score).

Exploratory Analysis: Checks data quality (no missing values) and visualizes feature relationships.

Preprocessing: Converts categorical features to numerical values.

Feature-Target Split: Separates input features and credit score target.

Model Training:

Random Forest: 97.54% accuracy (5-fold CV).

KNN: 95.72% accuracy (5-fold CV).

SVM: 90.88% accuracy (10-fold CV).


# Conclusion
This project showcases a complete machine learning workflow for credit score classification, with Random Forest as the top-performing model. It’s a practical example of applying machine learning to financial data, suitable for learning and further experimentation.
