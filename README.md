# Ensemble Modeling on Pima Indians Diabetes Dataset
This repository provides an in-depth implementation of ensemble modeling techniques including Boosting, Bagging, and Voting on the Pima Indians Diabetes Dataset. Ensemble methods combine the predictions from multiple models to improve accuracy and robustness, making them powerful tools in the field of machine learning.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Ensemble Techniques](#ensemble-techniques)
  - [Boosting](#boosting)
  - [Bagging](#bagging)
  - [Voting](#voting)
- [Results](#results)

## Introduction
This project demonstrates how to apply ensemble learning methods to classify whether a patient has diabetes based on diagnostic measurements. The three main ensemble techniques implemented are Boosting, Bagging, and Voting.

## Dataset
The Pima Indians Diabetes Dataset is used in this project. It consists of 768 samples of female patients of at least 21 years old of Pima Indian heritage. The dataset includes several medical predictor variables and one target variable indicating whether the patient has diabetes. The datset was taken from kaggle.

- **Features:**
  - Number of pregnancies
  - Plasma glucose concentration
  - Diastolic blood pressure
  - Triceps skinfold thickness
  - 2-Hour serum insulin
  - Body mass index (BMI)
  - Diabetes pedigree function
  - Age
- **Target:**
  - `0` (no diabetes)
  - `1` (diabetes)

## Ensemble Techniques

### Boosting
Boosting builds models sequentially, with each model attempting to correct the errors of the previous one. In this project, we implement:
- **AdaBoost**

### Bagging
Bagging involves training multiple models in parallel on different subsets of the data created through random sampling with replacement. In this project, we implement:
- **Bagging Classifier**

### Voting
Voting combines the predictions from multiple models (either bagging, boosting, or standalone models) and uses a majority vote or average for classification. In this project, we implement:


## Results
The results section in the Jupyter Notebook includes detailed evaluation metrics and visualizations to compare the performance of different ensemble methods. Key metrics include accuracy, precision, recall, F1-score.
