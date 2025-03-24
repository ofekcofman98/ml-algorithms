Logistic Regression – Exercise 3
This exercise focuses on implementing Logistic Regression from scratch using Python and NumPy, and applying it to both binary and multiclass classification tasks.

*Part 1 – Logistic Regression Class (Binary)
Implemented a custom LogisticRegression class using gradient descent.

Included:

fit(X, y) – training the model

predict(X) – binary prediction

proba_predict(X) – probability prediction

score(X, y) – accuracy

Stored weights in _weights.

*Part 2 – Spam Detection (Ham/Spam Dataset)
Used the spam_ham_dataset.csv.

Preprocessed text:

Lowercased, removed punctuation, filtered stopwords.

Transformed into numerical features using Bag-of-Words (CountVectorizer).

Trained the LogisticRegression model to classify emails as spam or not.

Printed accuracy and the weights vector.

*Part 3 – ROC Curve and Threshold Selection
Implemented ROC_curve() function using sklearn.metrics.roc_curve.

Plotted the ROC Curve for model evaluation.

Selected the optimal threshold using Youden's Index (TPR - FPR).

*Part 4 – Multiclass Classification (Iris Dataset)
Created MulticlassLogisticRegression using One-vs-Rest approach.

Trained the model on the Iris dataset with 3 classes.

Used:

StandardScaler to normalize input features

PolynomialFeatures (degree=2) to improve model performance

Printed accuracy and weight vectors for each class.

