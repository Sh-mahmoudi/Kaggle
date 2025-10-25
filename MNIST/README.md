# MNIST Dataset

This project applies Feedforward Neural Network models to handwritten digit classification on the MNIST dataset using PyTorch.


Data Source: [Kaggle-MNIST Dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset/data)


The Jupyter notebook `MNIST.ipynb` contains all data loading, device handling (CPU/GPU), training, evaluation, and accuracy measurement.



**Preprocessing**

The data were split into training and validation sets.

custom DataLoader wrappers were used to automatically move data to GPU or CPU

**Model Training**

The neural network used here is a fully connected (feedforward) model with one hidden layer.

It has three main parts:

Input layer: 784 units (for 28×28 pixels)

Hidden layer: 32 neurons with ReLU activation

Output layer: 10 neurons (for digits 0–9)

**Training and Evaluation**
The model is trained using the cross-entropy loss function.

The stochastic gradient descent (SGD) optimizer updates the model’s weights based on the computed gradients.

The evaluation process computes the average validation loss and accuracy over all batches in the validation set.


**Results**

The models achieved high accuracy (~91–93%).

The FNN was fast and produced good results


**Future Improvements**

Add dropout or batch normalization

Add convolutional layers (CNN) for higher accuracy

Implement early stopping
