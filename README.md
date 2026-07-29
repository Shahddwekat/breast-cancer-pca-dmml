# Breast Cancer Wisconsin Diagnostic — PCA and Model Comparison

Data Mining and Machine Learning course assignment.

Authors: Shahd Dwekat, Dana Samaro

## Overview

This project implements a complete machine learning workflow on the Breast Cancer Wisconsin Diagnostic dataset from the UCI Machine Learning Repository. It covers data preprocessing, Principal Component Analysis (PCA), and a comparison of three classifiers (Logistic Regression, Decision Tree, and SVM) trained on both the original and PCA reduced feature sets, evaluated using 5 fold cross validation and a held out test set.

## Dataset

The Breast Cancer Wisconsin Diagnostic dataset is used. It is loaded directly from scikit learn via load_breast_cancer(), so no manual download is required. The data is identical to the UCI Machine Learning Repository version, available at https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

The dataset contains 569 samples, 30 numeric features, and a binary target (malignant or benign).

## Requirements

This project requires Python 3.8 or higher, Jupyter Notebook, and the libraries numpy, pandas, scikit learn, and matplotlib. If you are using Anaconda, all of these are included by default. Otherwise, install them with:

```
pip install numpy pandas scikit-learn matplotlib jupyter
```

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Launch Jupyter Notebook by running: jupyter notebook
4. Open the file breast_cancer_pca.ipynb
5. Run all cells in order from top to bottom (Cell menu, then Run All).

The notebook is designed to run sequentially. Running cells out of order may cause errors, as later cells depend on variables defined earlier.

## Output

Running the notebook produces the dataset shape and class distribution, the preprocessing steps (missing value injection, imputation, and scaling), a PCA cumulative explained variance plot, the 5 fold cross validation results for all six model configurations, per class performance metrics for each model, and a confusion matrix for the best performing model.

## Files

The repository contains breast_cancer_pca.ipynb (the main notebook with all code) and README.md (this file). The technical report is submitted as a separate document.


Same reminder as before: run Kernel → Restart & Run All to confirm the notebook actually runs clean before you claim "run all cells in order" in the README. Fill in the two author names.
