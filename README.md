# Steganography CNN

This project contains a Convolutional Neural Network (CNN) model for detecting steganography in images. The model is trained using a dataset of images and is designed to distinguish between steganographic and non-steganographic images.

## Files

- `model_training.py`: Code for building, training, and saving the CNN model.

## Installation

To get started, make sure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- Keras
- Other dependencies (if any)

You can install the required dependencies using `pip`:

```bash
pip install tensorflow
pip install keras

Usage
To train the model, run the model_training.py file:

bash
Copy
python model_training.py

dataset/
    train/
        class_0/
        class_1/
    test/
        class_0/
        class_1/

