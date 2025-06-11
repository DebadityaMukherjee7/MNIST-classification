# 🧠 MNIST Digit Classification using TensorFlow

This project demonstrates a basic neural network built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

## 📚 Description

The notebook:
- Loads the MNIST dataset using `keras.datasets.mnist`
- Visualizes sample images using `matplotlib`
- Preprocesses the images by flattening and normalizing them
- Builds a simple neural network with:
  - One hidden layer with 100 neurons (ReLU activation)
  - Output layer with 10 neurons (Sigmoid activation)
- Trains the model for 10 epochs
- Evaluates model performance
- Visualizes the confusion matrix using `seaborn`

## 🛠️ Technologies Used

- Python
- TensorFlow & Keras
- NumPy
- Matplotlib
- Seaborn

## 🚀 How to Run

1. Install the required packages:
   ```bash
   pip install tensorflow matplotlib seaborn

