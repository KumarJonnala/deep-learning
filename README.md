# deep learning

Hands-on deep learning practice in PyTorch, working through core concepts from shallow networks to modern architectures. Notebooks follow the progression in *Deep Learning Illustrated* (Krohn, Beyleveld, Bassens) with extensions into transformers and beyond.

## Stack

- Python, PyTorch, torchvision, matplotlib
- Dataset: MNIST (digit classification throughout fundamentals)

## Notebook Index

### Foundations (Deep Learning Illustrated)

`1_shallow_net.ipynb`: Shallow neural network — forward pass, weights, biases/
`2_activation_functions.ipynb`: Sigmoid, tanh, ReLU — comparison and intuition/
`3_cost_functions.ipynb`: MSE and cross-entropy/
`4_intermediate_net.ipynb`: Intermediate layer neural network

In progress:
Convolutional Neural Networks (CNNs)
Recurrent Neural Networks (RNNs)
LSTMs
Transformers

---
## Neural Network Training

1. Initialise w, b
2. Forward pass -> output
3. Compute loss (output vs true label)
4. Backprop -> compute gradients for all w, b
5. Optimizer (SGD/Adam) -> update all w, b using gradients
6. Repeat for next batch
---

## Hyperparameters

learning rate: initialise with 0.001-0.01, adjust based on cost
batch size: initialise with 16-128, adjust based on compute and time
epochs
num of layers: initialise with 2-4 and adjust based on cost
num of neurons in a layer: start with 64 and just based on accuracy. 
    data with more low-level featuresmore -> additional neurons in network early layers
    data with high-level features -> additional neurons in network later layers 
Occam's razor: Simplest arch that can provide desired results is best.

---

## Concepts

parameters:
    weight w
    bias b
activation a
artificial neurons:
    sigmoid
    tanh
    ReLU
input layer
hidden layer
output layer
layer types:
    dense/fully connected
    softmax
cost/loss function
    MSE
    cross-entropy
forward propagation
back propagation
optimizers:
    stochastic gradient descent
optimizer hyperparameters:
    learning rate
    batch size

---


