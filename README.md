# Project Name: Handwritten Digit Recognition

This project implements and compares three machine learning algorithms for image classification: Support Vector Machine (SVM), Decision Tree, and Naive Bayes.

## Overview

The project uses a dataset of images (presumably handwritten digits, based on the context) to train and evaluate different classification models. The main steps include:

1. Data import and preprocessing
2. Feature selection and target variable definition
3. Train-test split
4. Model training and evaluation for three algorithms:
   - Support Vector Machine (SVM)
   - Decision Tree
   - Naive Bayes (Gaussian)
5. Comparison of model performances

## Requirements

- Python 3.x
- pandas
- scikit-learn

## Usage

1. Ensure you have the required libraries installed.

2. Place your dataset file (Dataset.csv) in the same directory as the script.

3. Run the script

## Results

The script compares the performance of three models:

1. Support Vector Machine (SVM):
- Accuracy: 95.81%
- Training time: 13.3 seconds

2. Decision Tree:
- Accuracy: ~80%
- Training time: 2.43 seconds

3. Naive Bayes:
- Naive Bayes does not perform well for this particular dataset

## Conclusion

Based on the results:

1. SVM performs the best with an accuracy of 96%, but has a longer training time.
2. Decision Tree provides a decent accuracy of about 80% with a significantly reduced training time.
3. Naive Bayes does not perform well for this particular dataset.

The Support Vector Machine algorithm appears to be the best choice for this project, balancing high accuracy with acceptable training time.

## Future Improvements

- Feature engineering to potentially improve model performance
- Hyperparameter tuning for each model
- Exploring other classification algorithms
- Analyzing misclassified instances to understand model weaknesses