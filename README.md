# 🐶🐱 Pet Image Classifier using CNN

This project is a Convolutional Neural Network (CNN) based image classifier that predicts whether an image is of a **Cat** or a **Dog**.

## 🚀 Features

- Built using TensorFlow and Keras
- Trained on labeled image data
- Preprocesses and resizes images to standard dimensions
- Achieves decent accuracy for binary image classification
- Includes prediction script to test on new images

## 🧠 Model Architecture

- Conv2D and MaxPooling layers
- Dropout for regularization
- Dense output with `softmax` activation

## 🗂️ Folder Structure

  Pet_classification/
  
    ├── Pet_classification.ipynb 

    ├── README.md 

    ├── requirements.txt # Dependencies

    ├── dog.jpg # Example test image (optional)

    └── model.h5 # Saved trained model (if available)

## 🛠️ Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt
