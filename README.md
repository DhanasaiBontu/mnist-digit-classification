# 🧠 MNIST Digit Classification  

This project implements a deep learning model using TensorFlow and Keras to classify handwritten digits (0-9) from the MNIST dataset. The model is trained and evaluated in a Jupyter Notebook.  

## 📌 Dataset  
The MNIST dataset consists of:  
- **60,000** training images  
- **10,000** test images  
- Images are **grayscale (28x28 pixels)**, representing digits from **0 to 9**  

## 🏗️ Model Architecture  
The model is a **Feedforward Neural Network (FNN)** with the following layers:  
- **Input Layer**: 784 neurons (flattened 28x28 image)  
- **Hidden Layer**: 512 neurons (ReLU activation)  
- **Dropout Layer**: 50% dropout for regularization  
- **Output Layer**: 10 neurons (Softmax activation for classification)  
