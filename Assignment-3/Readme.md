# Machine Learning Assignment 3: Cancer Dataset Classification

This repository contains the implementation of four different classification models to identify cancer types (Malignant vs. Benign) using the Breast Cancer dataset from scikit-learn.

## Assignment Overview

The assignment involves implementing and comparing the following models:
1. Logistic Regression (with and without regularization)
2. Naive Bayes Classifier
3. Support Vector Machine (SVM)
4. Logistic Regression with PCA Feature Extraction

## Dataset

The Breast Cancer Wisconsin dataset from scikit-learn contains 569 samples with 30 features each. The features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, describing characteristics of the cell nuclei present in the image.

## Implementation Details

### Problem 1: Logistic Regression

- Implementation of a logistic regression model using all 30 input features
- 80/20 train-test split with proper scaling and standardization
- Evaluation metrics: accuracy, precision, recall, and confusion matrix
- Model enhancement with regularization (weight penalty)

### Problem 2: Naive Bayes Classifier

- Implementation of a Naive Bayesian model for classification
- 80/20 train-test split
- Result visualization and comparison with the logistic regression model
- Analysis of performance differences between models

### Problem 3: SVM Classifier

- Implementation of an SVM classifier with a linear kernel
- 80/20 train-test split
- Comparison with previous models (logistic regression and naive Bayes)
- Experimentation with different kernel types (linear, poly, rbf, sigmoid)

### Problem 4: Logistic Regression with PCA

- Implementation of PCA for feature extraction before applying logistic regression
- Identification of the optimal number of principal components for classification
- Visualization of performance metrics across different numbers of components
- Comparison with full-feature models from previous problems

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

## File Structure

- `problem1_logistic_regression.ipynb`: Logistic regression implementation
- `problem2_naive_bayes.ipynb`: Naive Bayes classifier implementation
- `problem3_svm.ipynb`: SVM classifier implementation
- `problem4_pca_logreg.ipynb`: Logistic regression with PCA implementation

## Results

Each notebook includes detailed analysis of the model's performance, including:
- Classification metrics (accuracy, precision, recall, F1 score)
- Confusion matrices
- Feature importance analysis
- Model comparisons
- Visualizations of results

## Usage

1. Clone the repository
2. Install the required dependencies
3. Run each notebook to see the implementation and results for each classification method

## References

- The original assignment instructions and guidance notebooks can be found in the course materials
- scikit-learn documentation for:
  - [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
  - [Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)
  - [Support Vector Machines](https://scikit-learn.org/stable/modules/svm.html)
  - [PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)