# **Confusion Matrix and ROC Curve Implementation**

This project demonstrates how to evaluate a binary classification model using a Confusion Matrix and ROC Curve to assess performance on a sample dataset.

## **Project Overview**

The goal of this project is to implement a Confusion Matrix and ROC Curve for a binary classification problem. By visualizing these metrics, we aim to understand the accuracy and performance of a logistic regression model in distinguishing between two classes.

## **Key Components**

- **Confusion Matrix**: This metric summarizes the true positive, true negative, false positive, and false negative results, providing insights into model accuracy.
- **ROC Curve**: Plots the true positive rate (sensitivity) against the false positive rate, helping evaluate the trade-offs between true positive and false positive rates at various thresholds.

## **Dataset**

The dataset is synthetically generated, where:

- `X` contains 100 random samples with two features.
- `y` represents binary labels (0 or 1) assigned randomly.

## **Methodology**

1. **Data Splitting**: The dataset is divided into training and testing sets.
2. **Model Training**: Logistic Regression is used to train the model.
3. **Evaluation**:
   - Confusion Matrix is computed and visualized.
   - ROC Curve is plotted, and the Area Under the Curve (AUC) is calculated.

## **Results**

The Confusion Matrix and ROC Curve provide an in-depth look at the model’s classification performance. The ROC curve visualization aids in understanding the model’s ability to differentiate between the two classes.

