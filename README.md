

### Project Title: FashionMNIST Image Classification with PyTorch CNN

### Overview
This notebook builds, trains, and evaluates a Convolutional Neural Network (CNN) using PyTorch for image classification on the FashionMNIST dataset (60,000 training and 10,000 test images, 28x28 grayscale, 10 classes).

### Notebook Structure Highlights
1.  **Setup and Imports**: Essential libraries for PyTorch, data handling, and visualization.
2.  **Device Configuration**: Sets up GPU (if available) or CPU for computations.
3.  **Data Loading and Preprocessing**: Downloads FashionMNIST, transforms images to tensors, splits data, and scales pixel values.
4.  **Custom Dataset and DataLoader**: Defines custom dataset and data loaders for efficient batch processing.
5.  **Model Definition (CNN)**: Implements a CNN with convolutional layers, batch normalization, ReLU, dropout, max-pooling, and fully connected layers for classification.
6.  **Model Training**: Uses `CrossEntropyLoss` and SGD optimizer to train the CNN for 100 epochs.
7.  **Model Evaluation**: Calculates training and test accuracy to assess model performance.

### How to Run
Run all cells sequentially in a Google Colab or local PyTorch environment.

### Results
The trained CNN achieves high accuracy on both training and test sets of the FashionMNIST dataset.
