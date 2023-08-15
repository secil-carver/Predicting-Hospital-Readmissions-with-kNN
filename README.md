# KNN-Classification

[![](https://img.shields.io/badge/Python-blue?style=for-the-badge)](https://github.com/hamzamohdzubair/redant)
[![](https://img.shields.io/badge/ML-KNN-blueviolet?style=for-the-badge)](https://hamzamohdzubair.github.io/redant/)
[![](https://img.shields.io/badge/Library-Scikitlearn-yellow?style=for-the-badge)](https://docs.rs/crate/redant/latest)
[![](https://img.shields.io/badge/Library-Scipy-green?style=for-the-badge)](https://docs.rs/crate/redant/latest)
[![](https://img.shields.io/badge/Module-KNeighborsClassifier-orange?style=for-the-badge)](https://crates.io/crates/redant)

![](https://img.shields.io/static/v1?label=&message=Heatmap&color=green)
![](https://img.shields.io/static/v1?label=&message=GridSearch&color=orange)

Prediction using k-nearest neighbors classification method of patient hospital readmission.  

## Research Question

Can we predict patient readmissions using predictors such as the patient's age, if they had high or low Vitamin D levels, the number of doctor visits they had, or the total hospital charges they incurred while admitted initially?

## The Goal of the Data Analysis

The goal of this data analysis is to create a machine-learning model that can be used to identify patients who might be readmitted to our hospitals so not only that we can target these patients and make sure they receive the best comprehensive care when they are admitted, but by reducing readmission rates we can also try to minimize the penalties our hospitals incur due to patient readmissions.

## Technique Justification

KNN(K Nearest Neighbors) algorithm analyzes all the available data points such as patients' risk factors, if they were diabetic or not, and then check for class assignment. Then calculate the distance between training instances and the new case, then rank the distances as the nearest neighbors, then assign a classification to the new instance.

## Heat Map

![image](https://github.com/secil-carver/Predicting-Hospital-Readmissions-with-kNN/assets/77639654/5eb20c45-4a08-497b-b0b3-9650b590edc3)


## Grid Search

Visual interpretation of tuning technique that tries to find the optimum values of hyperparameters.

![image](https://github.com/secil-carver/Predicting-Hospital-Readmissions-with-kNN/assets/77639654/613d86d7-6f00-42e0-8227-abb067e1315e)


