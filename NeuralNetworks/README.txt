Neural Network Classifier
This project implements a fully connected feed-forward neural network from scratch using only NumPy, and applies it to both real-world tabular data and (optionally) the MNIST dataset.

The goal was to build a NeuralNetwork class from scratch to:
Train using backpropagation with Adam optimizer
Support batch normalization, dropout, and Leaky ReLU
Handle classification tasks with softmax output and categorical cross-entropy loss

*Features of NeuralNetwork Class
Arbitrary architecture: supports any number of hidden layers

Leaky ReLU activation + Batch Normalization

Dropout regularization

Adam optimizer for weight updates

Early stopping based on validation accuracy

One-hot encoding + Softmax output

High modularity: fit, predict, score, compute_loss, update_parameters, etc.

*Dataset & Preprocessing
Used MB_data_train.csv (tabular dataset with biological samples)

Preprocessing included:

Shuffling the dataset

Label encoding (fibro → 1, ctrl → 0)

Feature standardization using StandardScaler

Train/Validation split

*Model Training & Evaluation
Architecture: [input_size] → 128 → 64 → 32 → softmax

Used:

learning_rate = 0.0005

batch_size = 64

early_stopping_patience = 20

Evaluation:

Printed training and validation accuracy

Achieved optimized performance through parameter tuning

*Visualization
Used PCA to reduce the feature space to 2D

Visualized decision boundaries using contour plots

