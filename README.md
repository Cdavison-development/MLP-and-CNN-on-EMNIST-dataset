 This project is focused on building and optimizing neural network models to address the EMNIST classification challenge effectively. Deep neural networks are pivotal in various domains like computer vision, natural language processing, and medical image analysis, making the development of effective neural architectures for specific tasks increasingly crucial.

# Dataset
For this project, the EMNIST (Extended MNIST) dataset was utilized, which is an extension of the well-known MNIST dataset featuring handwritten character digits from the NIST Special Database 19, formatted into 28x28 pixel images. You can find the dataset here.

We opted for the "Balanced" split of the EMNIST dataset to ensure an equal representation of classes, which includes:

Training set: 112,800 images
Testing set: 18,800 images
Total: 131,600 images
Number of classes: 47 (balanced)

# Project Implementation
The primary goal is to write Python code to construct various neural networks and evaluate their performance. This involves implementing two types of neural networks:

Multilayer Perceptron (MLP) - This model should include at least three hidden layers.
Convolutional Neural Networks (CNNs) - This model should include at least two convolutional layers.

# Optimization Techniques
To achieve the best model performance, several techniques were explored:

Adaptive Learning Rate: Implemented at least two learning rate scheduling methods.
Activation Functions: Tested at least three types including ReLU, Leaky ReLU, and ELU.
Optimizers: Experimented with at least three optimizers such as SGD, ADAM, and RMSprop.
Batch Normalization: Evaluated models with and without batch normalization.
Regularization: Explored models with no regularization, L1 regularization, and L2 regularization.
Dropout: Assessed the impact of including dropout in the models.

# Strategy for Optimization
The approach started with establishing a baseline model configuration using prior deep learning knowledge. From there, each optimization technique was investigated individually to refine the model progressively:

Establish baseline with known configurations such as ReLU, ADAM, batch normalization, L2 regularization, and dropout.
Systematically explore and integrate the most effective techniques from each category to enhance model performance.
Hyperparameters
During the training phases of both MLPs and CNNs, careful consideration was given to the selection of suitable hyperparameters, including the number of hidden layers and the number of neurons in each layer.

 
