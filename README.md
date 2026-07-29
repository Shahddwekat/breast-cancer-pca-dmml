Breast Cancer Wisconsin (Diagnostic) PCA and Model Comparison
Data Mining and Machine Learning course assignment.
Authors: Shahd Dwekat, Dana Samaro
Overview
This project implements a complete machine learning workflow on the Breast Cancer Wisconsin (Diagnostic) dataset from the UCI Machine Learning Repository. It covers data preprocessing, Principal Component Analysis (PCA), and a comparison of three classifiers (Logistic Regression, Decision Tree, and SVM) trained on both the original and PCA-reduced feature sets, evaluated using 5-fold cross-validation and a held-out test set.
Dataset
The Breast Cancer Wisconsin (Diagnostic) dataset is used. It is loaded directly from scikit-learn via load_breast_cancer(), so no manual download is required. The data is identical to the UCI Machine Learning Repository version: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
The dataset contains 569 samples, 30 numeric features, and a binary target (malignant / benign).
Requirements
Python 3.8 or higher
Jupyter Notebook
The following Python libraries:
numpy
pandas
scikit-learn
matplotlib
If using Anaconda, all of these are included by default. Otherwise, install them with: pip install numpy pandas scikit-learn matplotlib jupyter

How to Run
Clone or download this repository.
Open a terminal in the project folder.
Launch Jupyter Notebook:
jupyter notebook

Open breast_cancer_pca.ipynb.
Run all cells in order, from top to bottom (Cell → Run All, or Shift+Enter through each cell).
The notebook is designed to be run sequentially. Running the cells out of order may cause errors, as later cells depend on variables defined in earlier ones.
Output
Running the notebook produces:
The dataset shape, class distribution, and missing-value check
The preprocessing steps (missing-value injection, imputation, scaling)
A PCA cumulative explained variance plot (Figure 1)
5-fold cross-validation results for all six model configurations
Per-class performance metrics (precision, recall, F1) for each model
A confusion matrix for the best-performing model (Figure 2)
Files
breast_cancer_pca.ipynb : the main Jupyter Notebook containing all code
README.md : this file
Technical report (separate document) : full written analysis of all tasks

