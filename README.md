# Multi-Layer Perceptron (MLP) Model for Binary Classification

## Project Overview
This project demonstrates the implementation of a **Multi-Layer Perceptron (MLP)** model for **binary classification** from scratch. The model is designed to classify input data into two categories (0 or 1). The MLP is built using **Python** and **NumPy**, with all neural network operations—such as forward propagation, backpropagation, and gradient descent—implemented without the use of deep learning libraries like TensorFlow or PyTorch.

The project provides a hands-on understanding of how neural networks work at a low level, giving users a deeper insight into the mechanics of an MLP.

## Features
- **Custom MLP Implementation**: Built from scratch using Python and NumPy, with no high-level deep learning frameworks.
- **Binary Classification**: Designed to solve binary classification problems (e.g., predicting 0 or 1).
- **Manual Backpropagation**: The model implements forward propagation, backpropagation, and weight updates using gradient descent manually.
- **Activation Functions**: ReLU for hidden layers and Sigmoid for the output layer.
- **Loss Function**: Binary cross-entropy for computing the model’s error.
- **Optimizer**: Gradient descent algorithm implemented from scratch.

## Dataset
The model is trained on a synthetic dataset generated using NumPy, which is included as an example. The dataset contains two classes, represented as 0 and 1, for training and testing the binary classification model.

Users can also use their own dataset by modifying the `data_loader.py` script.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Moshintha20/Multi-Layer-Perceptron-MLP-Model-for-Binary-Classification
   cd Multi-Layer-Perceptron-MLP-Binary-Classification
   ```

2. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Train the Model**:
   To train the MLP model on the default synthetic dataset, run the `main.py` script:
   ```bash
   python main.py
   ```

2. **Modify Hyperparameters**:
   You can modify key hyperparameters such as learning rate, number of epochs, and hidden layer size directly in the `main.py` script to experiment with different settings.

3. **Customize Dataset**:
   To use your own binary classification dataset, modify the `data_loader.py` file to load your data in the correct format.

4. **Evaluation**:
   After training, the script will display performance metrics such as accuracy and loss, and it will plot the training history.

## Model Architecture

- **Input Layer**: Neurons equal to the number of input features in the dataset.
- **Hidden Layer**: Fully connected layer using the ReLU activation function.
- **Output Layer**: A single neuron with Sigmoid activation to predict binary outcomes (0 or 1).
- **Loss Function**: Binary cross-entropy for computing the loss between the predicted and actual values.
- **Optimizer**: Gradient descent algorithm implemented from scratch for optimizing the weights.

## Example
Using a synthetic dataset for binary classification, the model achieved over 90% accuracy after training for 500 epochs.

## Results
- **Accuracy**: The MLP model performs well on binary classification tasks, achieving high accuracy.
- **Loss Plot**: The training loss consistently decreases, indicating successful learning.

## How to Customize
- Modify `main.py` to adjust the model architecture (e.g., add more hidden layers or neurons).
- Replace the synthetic dataset with a custom dataset in `data_loader.py` to train the model on real-world data.

## Requirements
Install the following Python dependencies:
```txt
numpy
matplotlib
```
