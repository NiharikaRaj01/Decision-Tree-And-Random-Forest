## Decision Tree and Random Forest Implementation
This repository contains a custom implementation of Decision Tree and Random Forest algorithms using Python, along with a demonstration of their functionality on a 2D classification problem.

Overview
Decision Tree: A supervised machine learning algorithm used for both classification and regression tasks. It recursively splits data based on feature values to create a tree-like structure.
Random Forest: An ensemble method that combines multiple decision trees to improve accuracy and reduce overfitting. Each tree in the forest is trained on a random bootstrap sample of the data, and the final prediction is based on the majority vote from all trees.
Key Features
Decision Tree:

Supports both classification and regression.
Uses entropy and information gain for feature selection.
Can handle categorical and continuous data.
Random Forest:

Ensemble of multiple decision trees.
Bootstrap sampling and random feature selection during training.
Reduces overfitting and improves prediction accuracy.
Implementation Details
Node Class: Defines the structure of a node in the decision tree, including the feature used for splitting, threshold value, and pointers to left and right child nodes.
Decision Tree Class:
Recursively grows the tree based on the best feature splits.
Uses entropy and information gain to select the best features.
Prunes the tree when necessary to avoid overfitting.
Random Forest Class:
Trains multiple decision trees using bootstrap samples.
Aggregates predictions from all trees to make final predictions.
Dependencies
numpy
matplotlib (for visualization)
Usage
Training:
Instantiate the DecisionTree or RandomForest class.
Use the fit(X, y) method to train the model on the dataset.
Prediction:
Use the predict(X) method to make predictions on new data.
