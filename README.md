# 🐾 Cat vs Dog Image Classifier

A Convolutional Neural Network (CNN) built using Python and TensorFlow to classify images as either cats or dogs.

## 📌 Overview

This project demonstrates how to build and train a binary image classification model from scratch. The model uses a labeled dataset of cat and dog images to learn distinguishing features and predict the correct category. This project was built following the instructions given in the Machine Learning with Python certification from freeCodeCamp: https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/cat-and-dog-image-classifier

The project is ideal for understanding:

- Image preprocessing and augmentation
- Convolutional Neural Networks (CNNs)
- Binary classification
- Overfitting control and model evaluation

## 🛠 Technologies Used

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab or Jupyter Notebook

## 🚀 Features

- Data loading and visualization
- Image augmentation for training robustness
- Custom CNN architecture
- Training and validation with real-time accuracy and loss tracking
- Model evaluation on unseen data

## 📊 Model Architecture

The CNN includes:

- Multiple `Conv2D` and `MaxPooling2D` layers
- A `Flatten` layer followed by dense `Dense` output with sigmoid activation

## 📈 Results

The model reaches strong validation accuracy and generalizes well on unseen data, demonstrating effective binary classification capabilities.

Example output metrics:

- **Training Accuracy:** ~68%
- **Validation Accuracy:** ~72%
- **Testing Accuracy:** ~70%

*(Exact results may vary depending on dataset splits and training conditions.)*

## 🧠 How It Works

1. Images are resized to a consistent shape (e.g., 150x150 pixels).
2. Data is split into training and validation sets.
3. Augmentation techniques (rotation, zoom, flip, etc.) are applied.
4. The CNN learns from the training data and is evaluated using validation data.
5. Final model can predict new unseen cat/dog images.

## 📌 Future Improvements
Currently, the model has ~70% accuracy which is a good starting point to improve upon in future updates. The model also has a 68% training accuracy which shows that the model generalizes very well since the training accuracy and validation accuracy are relatively equal. This leaves room some room for improvement by:
mplement early stopping and learning rate scheduling

1. Experimenting with pretrained models
2. Increasing the epochs or decreasing the batch size (may introduce overfitting)
3. Experimenting with learning rate scheduling and early stopping
4. Increasing the model complexity by adding more layers or increasing the number of filters in each layer
5. Use a more diverse training dataset
