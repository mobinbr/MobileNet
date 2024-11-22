# MobileNet Training on CIFAR-100

This project demonstrates the training of a MobileNetV2 model on the CIFAR-100 dataset. It includes functionality for creating balanced subsets, defining data loaders, and training with different optimizers.

## Features

- **Balanced Dataset Subset Creation**: Sample subsets with equal representation of each class.
- **Data Augmentation and Normalization**: Resize, normalize, and prepare the data for training.
- **Model Definition**: MobileNetV2 with custom classification layers tailored to the CIFAR-100 dataset.
- **Training and Evaluation**: Train the model with various optimization algorithms and evaluate performance on validation and test datasets.

## Usage

### 1. Dataset Preparation

The notebook automatically downloads and prepares the CIFAR-100 dataset. A balanced subset is created for training and testing.

### 2. Training

The model is trained on only 10% of the CIFAR-100 dataset to demonstrate the workflow. As a result, the accuracy is expected to be low. For better performance, consider training the model on the full dataset.

Run the training loop using different optimization algorithms. Supported optimizers include:

- SGD
- SGD with Momentum
- RMSprop
- Adadelta
- Adagrad
- Adam


### 3. Metrics and Evaluation

The notebook tracks:

- Training and validation losses
- Training and validation accuracies
- Final test accuracy

### 4. Results

Evaluate the performance of the trained model on the test dataset.
