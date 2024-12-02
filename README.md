# MNIST Image Classification using CNN

This project demonstrates a Convolutional Neural Network (CNN) model for classifying handwritten digits from the MNIST dataset. The MNIST dataset contains grayscale images of handwritten digits ranging from 0 to 9. The model is implemented in Python using TensorFlow and Keras.


## Introduction
This project uses the MNIST dataset to train a CNN model capable of classifying digits. It includes:
- Preprocessing the dataset by reshaping and normalizing the data.
- Training a CNN model with multiple convolutional and pooling layers.
- Evaluating the model’s accuracy on the test dataset.
- Visualizing training performance and making predictions.

---

## Technologies Used
- Python
- TensorFlow
- Keras
- Matplotlib
- Numpy

---

## Dataset
The MNIST dataset consists of 60,000 training images and 10,000 testing images. Each image is:
- 28x28 pixels
- Grayscale (1 channel)
- Labeled with a digit (0-9)

---

## Model Architecture
The CNN model consists of:
1. **Input Layer**: Accepts 28x28 grayscale images.
2. **Convolutional Layers**: 
   - 32 filters with a 3x3 kernel.
   - 64 filters with a 3x3 kernel.
3. **Pooling Layers**: Max pooling with a 2x2 kernel.
4. **Fully Connected Layers**:
   - Dense layer with 64 units and ReLU activation.
   - Dense output layer with 10 units and softmax activation.
5. **Optimizer**: Adam
6. **Loss Function**: Sparse Categorical Crossentropy

