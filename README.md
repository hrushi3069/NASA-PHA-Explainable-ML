Explainable Machine Learning for the Classification of Potentially Hazardous Asteroids

This repository contains the code developed for an MSc Data Analytics dissertation at the University of Brighton. The project applies machine learning techniques to classify Potentially Hazardous Asteroids (PHAs) using orbital and physical characteristics from NASA/JPL data.

The analysis includes data preprocessing and missing-value imputation, class-imbalance handling, Random Forest classification, model evaluation, and SHAP-based explainable machine learning to identify the most influential features in PHA classification.

Contents
Data preprocessing and cleaning
Missing-value imputation
Exploratory data analysis
Random Forest classification
Class-weighted Random Forest
SMOTE-based classification
Model evaluation using precision, recall, F1-score and PR-AUC
SHAP explainability analysis
Feature importance analysis
Visualisations and model results
Dataset

The dataset is based on NASA/JPL Small-Body Database orbital and physical information. The original dataset is not included in this repository due to its size. Please refer to the dissertation for the complete dataset description and source.

Technologies
Python
Pandas
NumPy
Scikit-learn
Imbalanced-learn
SHAP
Matplotlib
Seaborn
Purpose

The purpose of this project is to investigate whether machine learning can effectively classify Potentially Hazardous Asteroids while providing interpretable explanations of the factors influencing model predictions.

This repository accompanies the MSc Data Analytics dissertation and is provided for academic and reproducibility purposes.
