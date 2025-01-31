# Advanced Machine Learning Pipeline for Mammographic Mass Classification

This project implements a comprehensive machine learning pipeline for classifying mammographic masses as benign or malignant, aiming to enhance breast cancer diagnosis accuracy.

## Overview

The system incorporates data preprocessing, model training, and evaluation of three supervised learning algorithms:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

Utilising a dataset of 961 cases, the SVM model demonstrated superior performance, achieving an accuracy of 0.848 and an F1-Score of 0.823, compared to 0.807 and 0.763 for the BI-RADS model alone.

## Features

- Data preprocessing including handling missing values and normalisation
- Implementation and comparison of multiple machine learning models
- Comprehensive evaluation metrics including accuracy, F1-score, and ROC curves
- Comparison with traditional BI-RADS-based classification method

## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Usage

1. Clone the repository
2. Install the required dependencies
3. Run the Jupyter notebook or Python script to execute the pipeline

## Results

The SVM model outperformed both other machine learning models and the traditional BI-RADS approach, demonstrating potential for improving breast cancer screening accuracy and reducing unnecessary biopsies.

## Future Work

- Incorporate deep learning models for comparison
- Explore feature engineering techniques to further improve performance
- Conduct clinical trials to validate the model's effectiveness in real-world scenarios

## Contact

For collaboration or enquiries, please contact:

Bruno Sousa
Email: brunolopessousa23@gmail.com
