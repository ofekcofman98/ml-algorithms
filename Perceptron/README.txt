# Exercise G – Perceptron Classifier

## Description

In this exercise, we implemented a **Perceptron** classifier from scratch to perform binary classification. The task involved both **building the Perceptron algorithm** and **applying it to a real-world dataset**.

### Goals of the Exercise
1. **Implement a `Perceptron` class** that:
   - Includes a `fit(X, y)` method to train the model using features `X` and labels `y`, based on the classic Perceptron update rule.
   - Stores the learned weight vector `W` and bias `b`.
   - Includes a `predict(X)` method that returns predictions for new data points.
   - Includes a `score(X, y)` method to compute classification accuracy.

2. **Test the model on a small synthetic dataset** to verify the implementation.

3. **Apply the algorithm to a real dataset** — the **Processed Wisconsin Diagnostic Breast Cancer dataset** (`Cancer.csv`):
   - Relabeled diagnoses: `1` for malignant, `-1` for benign.
   - Data shuffled and split into 80% train / 20% test.
   - Reported accuracy and training error.

### Key Concepts Covered
- Binary classification using a linear model
- Perceptron learning rule
- Accuracy calculation
- Preprocessing and cleaning real-world data
