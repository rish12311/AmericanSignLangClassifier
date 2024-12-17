# ASL Hand Gesture Recognition using Convolutional Neural Networks (CNN)

This project implements a Convolutional Neural Network (CNN) to recognize American Sign Language (ASL) hand gestures. The model classifies grayscale hand gesture images (28x28 pixels) into corresponding alphabetic letters A-Z. The primary goal of this project is to automate the recognition of ASL gestures and enhance communication accessibility.

## Dataset

- **Images**: Grayscale hand gesture images representing the letters A-Z.
- **Image Size**: 28x28 pixels.
- **Classes**: 26 classes corresponding to the letters A-Z (excluding J and Z).

## Model Architecture

- **Input Layer**: 28x28 grayscale images.
- **Convolutional Layers**:
  - Two convolutional layers with learnable filters.
  - ReLU activation function.
  - Max pooling layers to reduce spatial dimensions.
- **Fully Connected Layer**:
  - A fully connected layer with a dropout rate of 0.28 to prevent overfitting.
- **Output Layer**:
  - 26 output nodes representing the letters A-Z.
  
## Key Features

- Automated sign language letter recognition.
- Deep learning approach using Convolutional Neural Networks.
- Aims to improve communication accessibility by automating ASL recognition.

## Performance Metrics

- **Classification Accuracy**: Measure of how accurately the model classifies the gestures.
- **Loss Minimization**: The model aims to minimize the loss function (cross-entropy) during training.

## Requirements

- Python 3.x
- TensorFlow/Keras
- NumPy
- Matplotlib

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/asl-hand-gesture-recognition.git
   cd asl-hand-gesture-recognition
