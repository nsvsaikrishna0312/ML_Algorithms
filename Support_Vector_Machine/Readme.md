# Support Vector Machine (SVM) Algorithm 

## Overview

This repository contains an implementation of the Support Vector Machine (SVM) algorithm, a powerful supervised learning model used for classification and regression tasks. SVM is particularly effective in high-dimensional spaces and is widely used in various applications.

### Here are the definitions for the key terms in SVM:

1. **Hyperplane**: A decision boundary that separates data points into different classes.
2. **Support Vectors**: Data points closest to the hyperplane that define the margin.
3. **Margin**: The distance between the hyperplane and the closest support vectors.
4. **Kernel**: A function that transforms data into a higher-dimensional space to enable linear separation.
5. **C (Regularization Parameter)**: A parameter that controls the trade-off between margin size and misclassification.
6. **Support Vector Classifier (SVC)**: An SVM model used for classification tasks.
7. **Soft Margin SVM**: SVM that allows some misclassification for better generalization.
8. **Hard Margin SVM**: SVM that requires perfect separation of data without misclassification.
9. **Support Vector Regression (SVR)**: An SVM model used for regression tasks, predicting continuous values.
10. **Dual Problem**: The formulation of the SVM problem that involves optimizing Lagrange multipliers.
11. **Lagrange Multipliers**: Parameters used in the dual problem formulation to optimize the SVM model.
12. **Slack Variables**: Variables that allow for misclassification in soft margin SVM.
13. **Class Separation**: The process of dividing data into classes using a decision boundary.
14. **Cost Function (Objective Function)**: A function that measures the error in the SVM model's predictions.
15. **Optimization**: The process of adjusting model parameters to minimize error and maximize the margin.
16. **Linear SVM**: An SVM that works with linearly separable data.
17. **Non-Linear SVM**: An SVM that uses kernels to separate non-linearly separable data.

<img src="https://www.theclickreader.com/wp-content/uploads/2020/07/SVC-1536x864.png" alt="Alt Text" width="500" height="300" />

## Features
- Implementation of SVM for classification and regression
- Support for different kernel functions (linear, polynomial, RBF, etc.)
- Hyperparameter tuning using grid search
- Visualization of decision boundaries

## Installation

To use this repository,you can clone the repository and run the files.

```bash
git clone https://github.com/nsvsaikrishna0312/svm-algorithm.git
cd svm-algorithm
