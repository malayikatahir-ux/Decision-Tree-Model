Project Overview

This project demonstrates the complete implementation of the Decision Tree Machine Learning Algorithm using the classic Play Tennis Dataset. The goal of this project was not only to train a machine learning model, but also to deeply understand how a Decision Tree makes logical decisions step by step.

Instead of directly applying the algorithm through code, the project first begins with manual handwritten calculations of entropy and feature splitting to understand the mathematical reasoning behind every branch of the tree. After the theoretical understanding, the same dataset is implemented programmatically using Python and Scikit-learn.

Dataset Used

The project uses a small categorical dataset containing 14 records with the following features:

Weather → Sunny, Rainy, Overcast
Humidity → High, Normal
Wind → Weak, Strong
Target Variable (Play) → Yes / No

The objective of the model is to predict whether a person should play tennis based on weather conditions.

Workflow of the Project
1. Handwritten Decision Tree Calculations

Before coding, entropy and decision splits were manually calculated to understand:

Information Gain
Feature selection
Root node selection
Branch creation logic
Decision-making process of the algorithm

Handwritten notes and tree diagrams are included in the repository images.

2. Data Preprocessing

The categorical data was converted into numerical form using encoding techniques so it could be processed by the Decision Tree model.

3. Model Training

The Decision Tree Classifier was trained using:

Scikit-learn
Entropy criterion
Encoded categorical features
4. Decision Tree Visualization

The trained model was visualized using Matplotlib to observe:

Feature splits
Decision paths
Sample distribution
Predicted classes
5. Prediction & Accuracy Analysis

The model predictions were analyzed and compared with the handwritten calculations to verify whether the coded implementation followed the same logical structure.

The project also explores:

Why manually calculated trees and generated trees may differ
Entropy vs Gini differences
Impact of train-test split on small datasets
📈 Output of the Project

After training, the model successfully:
 Learned decision-making patterns from weather conditions
 Predicted whether tennis should be played or not
 Generated a visual decision tree diagram
 Demonstrated how machine learning models create rule-based decisions

Example output rules:

Overcast → Play = Yes
Sunny + High Humidity → Play = No
Rainy + Weak Wind → Play = Yes
🛠 Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Learning Objective

This repository focuses on building strong machine learning foundations by combining:

Theoretical understanding
Mathematical reasoning
Practical implementation
Visualization
Debugging and analysis

The purpose of this project is to learn Machine Learning from scratch with deep conceptual clarity instead of relying only on pre-written code.
