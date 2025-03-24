Support Vector Machines (SVM):

This exercise focuses on implementing both linear and kernel-based SVMs from scratch, solving their primal and dual forms, and evaluating different kernel configurations on real and synthetic datasets.

*Question 1 – Linear SVM (Primal & Dual)
Used the dataset: simple_classification.csv

Implemented:
The primal form of the SVM optimization problem
The dual form using quadratic programming

Plotted:
The decision boundary
Margin lines
Support vectors (for the dual form)

Printed the learned weight vector w

*Question 2 – Kernel SVM (Dual with Kernels)
Used the dataset: simple_nonlin_classification.csv

Implemented the SVM dual form with kernels
Tried different kernels:
Polynomial kernel with degrees 2, 3, 4
RBF kernel with γ = 0.1, 1, 10

For each kernel:
Trained and tested the model
Compared train/test error
Plotted an error bar chart
Visualized best models:
Non-linear decision boundaries
Margin curves
Support vectors

*Question 3 – SVM Class
Implemented an SVM class with an interface similar to sklearn.svm.SVC

Supported:
__init__ (kernel type, degree, C, gamma)
fit, predict, score, decision_function
Supported RBF and Polynomial kernels
Used quadratic programming to solve the dual problem

*Question 4 – Breast Cancer Dataset (Real Data)
Used the Processed Wisconsin Diagnostic Breast Cancer.csv dataset
Applied the custom SVM class to the real-world dataset
Compared different kernels and parameters on real data
Plotted train/test error for each kernel configuration

