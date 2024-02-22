# Keras-Vs.-PyTorch-Comparison
Just an experimental Python file to compare models offered by Keras and PyTorch

# Description

This project aims to explore and compare the capabilities, syntax, and performance of two leading deep learning frameworks: TensorFlow/Keras and PyTorch, using the classic MNIST handwritten digit recognition task as a benchmark.

The MNIST dataset, consisting of 60,000 training images and 10,000 test images of handwritten digits, serves as an excellent platform for benchmarking machine learning models. In this notebook, we delve into creating and training neural network models to classify these digits, first using TensorFlow/Keras and then replicating the same model architecture using PyTorch.

## Key aspects covered include:
- Data preprocessing and exploration.
- Model architecture design and implementation in both frameworks.
- Training and evaluation of models.
- Comparison of accuracy, performance, and ease of use between TensorFlow/Keras and PyTorch.


With a detailed walkthrough, this project not only highlights the strengths and weaknesses of each framework but also serves as a practical guide for those looking to understand or choose between TensorFlow/Keras and PyTorch for their projects.

## Technologies Used:

- Python
- TensorFlow/Keras
- PyTorch
- Jupyter Notebook

## Model Architecture
The core of this comparison lies in the model architecture replication across both frameworks. The neural network models designed for this task are kept identical in terms of layer configurations to ensure a fair comparison.

*TensorFlow/Keras Implementation*

In TensorFlow/Keras, the model is built using the Sequential API, allowing for a clear and intuitive stack of layers. The architecture typically consists of a series of Dense (fully connected) layers, with ReLU activations for non-linearity and a final Softmax layer for classification. Keras provides a very high-level abstraction, making it straightforward to define the model, compile it with a chosen optimizer and loss function, and fit it to the data.

*PyTorch Implementation*

Transitioning to PyTorch, the model architecture is defined within a class that inherits from torch.nn.Module. This approach requires a more explicit definition of the forward pass but offers greater flexibility. Like in Keras, the PyTorch model employs fully connected layers with ReLU activations, concluding with a Softmax function for the output layer. PyTorch's dynamic computation graph contrasts with Keras's static graph, presenting a different paradigm in model implementation and debugging.

## Evaluation and Comparison

The models are evaluated based on their accuracy on the test dataset. This project demonstrates that despite the syntactical and paradigm differences between TensorFlow/Keras and PyTorch, both frameworks are capable of achieving comparable performance on the MNIST dataset. However, the ease of use, flexibility, and control offered by each framework can influence the choice depending on the user's preferences and the specifics of the project.
