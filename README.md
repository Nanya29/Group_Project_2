# Group_Project_2

## Overview of the Analysis

* This repo aims to use a diverse range of models to both predict if someone has breast cancer, and seperately, catagorize their breast cancer type.
* We use the following data sets to train and test our models:

    * [Breast Cancer Wisconsin - UC Irvine](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

    * [BRCA - Kaggle](https://www.kaggle.com/datasets/amandam1/breastcancerdataset)
 
# Data Analysis

Data collection began by fetching a CSV file from Kaggle.

Following collection, the dataset underwent cleaning to address categorical, and continuous data with varying scales. Cleaning involved scaling.

Processing involved the use of various built-in Python functions and specialized libraries, with sklearn being the primary tool for data processing.

For analysis, visualization packages like Matplotlib and Seaborn were utilized to create compelling representations of model confusion matrix.






# Dependencies

- `python`
- `pandas`
- `tensorflow`
- `sklearn`
- `ucimlrepo`
- `matplotlib`
- `ploty`

# Results

## BC Dataset
- 96.5% Accurate (Neural Network)
- 99% training, 98% testing Accuracy (LR Model)
- 100% training, 98% testing Accuracy (XGB Classifier Model)
- 95.6% accurate (SVM)

## BRCA Dataset
- 68.75% Accurate (Sequential Neural Network)
- 64.29% Accurate (Neural Network)
- 58.20% Accurate(SVM)
- 55% Accurate(KNN)
