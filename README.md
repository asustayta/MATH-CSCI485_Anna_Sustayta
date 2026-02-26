# MATH-CSCI485_Anna_Sustayta
Adv Topics in Data Science Spring 2026

# Assignment 2- Recursive Feature Elimination

## Overview
This project implements Recursive Feature Elimination

The goal is to :
 - Build a baseline linear regression model
 - Implement custom RFE that eleiminates one feature at a time
 - Track Test $R^2$ across iterations
 - Determine the optimal number of features using a threshold approach
 - Analyze the most important predictors

--- 

## Files Included

- Assignemnt2.ipynb - Jupyter notebook containing all code, outputs, plots, and tables made with google colab
- Assignment2.pdf - 3 pages written report with analysis and interpretations

---

## Execution

requires:
- numpy
- pandas
- matplotlib
- scikit-learn

---
## Summary

- Baseline Test $R^2 = 0.4526$
- Optimal number of features (k) = 3
- Most important features:
    - s5
    - bmi
    - s1
 
RFE showed that a small subset of features will result in the most efficient model.
  
