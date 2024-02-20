# Fraud detection - dealing with imbalanced data

## Overview
The Credit Card Fraud Detection project tackles the challenge of identifying fraudulent transactions within highly imbalanced datasets buy comparing some of the popular techniques. The primary goal is to compare different techniques for dealing with imbalanced data to minimize the impact on legitimate users while accurately identifying fraudulent activities, thereby reducing false positives.

## Prerequisites
Before running the code, ensure you have the following libraries installed:

- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn

## Approaches to Address Imbalance
- Weighting Loss Function: Adjusts the loss function to account for imbalanced class distribution by adding penalties to the minority class.
- Undersampling: Reduces the size of the majority class to balance the dataset, including techniques like Random undersampling and Near-Miss.
- Oversampling: Increases the size of the minority class, using methods such as Random oversampling, SMOTE (Synthetic Minority Over-sampling Technique), and ADASYN (Adaptive Synthetic).
