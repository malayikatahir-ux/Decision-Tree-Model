<div align="center">

# Decision Tree Model

### From Handwritten Calculations to Model Implementation Using Python & Scikit-learn

</div>

---

## Project Overview

This project demonstrates the complete implementation of the **Decision Tree Machine Learning Algorithm** using the classic **Play Tennis Dataset**.  

The primary goal of this project is not only to train a machine learning model, but also to deeply understand how a Decision Tree makes logical decisions step by step.

Instead of directly applying the algorithm through code, the project first begins with **manual handwritten entropy and information gain calculations** to understand the mathematical reasoning behind every split and branch of the tree.  

After the theoretical understanding, the same dataset is implemented programmatically using **Python** and **Scikit-learn**.

---

# Dataset Information

The dataset contains **14 records** with the following features:

| Feature | Description |
|---|---|
| Weather | Sunny, Rainy, Overcast |
| Humidity | High, Normal |
| Wind | Weak, Strong |
| Play | Yes / No (Target Variable) |

### Objective
The model predicts whether a person should play tennis based on weather conditions.

---

# Project Workflow

## 1. Handwritten Decision Tree Calculations
Before coding the model, entropy and information gain calculations were manually performed to understand:

- Feature selection
- Root node creation
- Decision splitting
- Branch generation
- Tree decision logic

Handwritten notes and manually created tree diagrams are included in the repository images.

---

## 2. Data Preprocessing
Categorical features were encoded into numerical values so they could be processed by the Decision Tree model.

Techniques used:
- Label Encoding
- Ordinal Encoding
- One Hot Encoding

---

## 3. Model Training
The Decision Tree Classifier was trained using:


DecisionTreeClassifier(criterion='entropy')

Libraries used:

Pandas
NumPy
Scikit-learn
Matplotlib.pyplot

---

## 4. Decision Tree Visualization

The trained model was visualized using Matplotlib to analyze:

Feature splits
Decision paths
Sample distribution
Predicted outcomes

---

## 5. Prediction & Analysis

The generated Decision Tree was compared with the manually calculated tree to understand:

How the algorithm selects features
Why generated trees may differ from handwritten trees
Difference between Entropy and Gini methods
How small datasets affect model accuracy

---

## 6. Project Output

The trained model successfully:

Learned patterns from weather conditions
Predicted whether tennis should be played or not
Generated a visual decision tree diagram
Demonstrated rule-based machine learning predictions
Example Learned Rules
Condition	Prediction
Overcast	Play = Yes
Sunny + High Humidity	Play = No
Rainy + Weak Wind	Play = Yes
Technologies Used
Technology	Purpose
Python	Programming Language
Pandas	Data Handling
NumPy	Numerical Operations
Scikit-learn	Machine Learning
Matplotlib	Visualization

---

## 7. Learning Objective

This repository focuses on building strong conceptual understanding of Decision Trees by combining:

Mathematical reasoning
Handwritten calculations
Practical implementation
Visualization
Model analysis
Debugging and experimentation

The purpose of this project is to learn Machine Learning from scratch with deep conceptual clarity instead of relying only on pre-written code.

---

<div align="center">
Repository Includes

Handwritten Calculations • Decision Tree Diagrams • Python Implementation • Model Visualization • Prediction Analysis

---
</div> 
