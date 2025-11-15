## Iris Flower Classification using Decision Tree Classifier

A complete Machine Learning project that uses a Decision Tree model to classify Iris flower species. The project includes model training, evaluation, and full decision-tree visualization.

## 📌 Project Overview

This project builds a Decision Tree classifier using the Iris dataset. Decision Trees are intuitive models that split data based on feature thresholds to make predictions.

Dataset contains 150 samples across 3 classes:

Setosa

Versicolor

Virginica

## 🧠 Objectives

Understand how Decision Trees work

Visualize model decision rules

Evaluate classification performance

Learn model interpretability through tree plots

## **🛠️ Workflow**
**1. Load Dataset**

Used scikit-learn’s built-in Iris dataset.

**2. Preprocessing**

Defined features (X) and labels (y)

**3. Train-Test Split**

80% training

20% testing

**4. Model Training**

Trained Decision Tree Classifier:

DecisionTreeClassifier()

**5. Prediction**

Predicted classes for test data.

**6. Evaluation**

Calculated accuracy using:

accuracy_score(y_test, y_pred)

**7. Visualization**

Generated a full Decision Tree plot using:

plot_tree(model, filled=True)


## Saved visualization:
tree_visual(1).png

🌳 Decision Tree Visualization

## 📊 Results

Test Accuracy: 1.0
High accuracy is common on Iris because decision trees can easily separate the classes.

## 📦 Technologies Used

Python

scikit-learn

NumPy

Pandas

Matplotlib

▶️ How to Run the Project
1. Install dependencies:
pip install -r requirements.txt

2. Run:
python decision_tree.py

## 📚 What I Learned

How Decision Trees split data based on impurity

Gini Impurity and entropy basics

Visualizing model decisions

Understanding overfitting

