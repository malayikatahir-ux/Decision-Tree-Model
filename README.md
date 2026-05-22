Project Overview

This project demonstrates the complete implementation of the Decision Tree Machine Learning algorithm using the classic Play Tennis dataset. The main goal of the project is to understand how a Decision Tree makes decisions step by step instead of only training a model through code.

The project starts with handwritten entropy and information gain calculations to understand the logic behind feature selection and tree splitting. After understanding the theoretical part, the same dataset is implemented programmatically using Python and Scikit-learn.

Dataset Information

The dataset contains 14 records with the following features:

Weather → Sunny, Rainy, Overcast
Humidity → High, Normal
Wind → Weak, Strong
Target Variable (Play) → Yes / No

The objective of the model is to predict whether a person should play tennis based on weather conditions.

Project Workflow
1. Manual Decision Tree Calculations

The project begins with handwritten calculations of:

Entropy
Information Gain
Feature selection
Root node identification
Branch creation logic

Handwritten notes and tree diagrams are included in the repository.

2. Data Preprocessing

Categorical features were encoded into numerical values so they could be processed by the machine learning model.

3. Model Training

The Decision Tree Classifier was trained using:

Python
Pandas
Scikit-learn
Entropy criterion
4. Decision Tree Visualization

The trained model was visualized using Matplotlib to analyze:

Feature splits
Decision paths
Sample distribution
Final predictions
5. Prediction and Analysis

The generated decision tree was compared with the manually calculated tree to understand:

How the algorithm selects splits
Why different trees can still be logically correct
The difference between entropy and gini-based trees
Output of the Project

The trained model successfully:

Learned patterns from weather conditions
Predicted whether tennis should be played or not
Generated a visual decision tree structure
Demonstrated rule-based machine learning predictions

Example learned rules:

Overcast → Play = Yes
Sunny + High Humidity → Play = No
Rainy + Weak Wind → Play = Yes
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Learning Objective

This project focuses on building strong conceptual understanding of Decision Trees by combining theoretical calculations with practical implementation. The repository reflects a learning approach based on understanding, experimentation, visualization, and debugging instead of simple copy-paste coding.
