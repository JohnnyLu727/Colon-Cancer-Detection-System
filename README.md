# Colon Cancer Detection using Deep Learning

A convolutional neural network for classifying colon histopathology images as normal or cancerous tissue.

## Results
- **Accuracy**: 88%
- **Normal tissue precision**: 1.00 
- **Cancer tissue precision**: 0.81
- **Dataset**: 10,000 colon histopathology images

## Technologies
- TensorFlow/Keras
- Computer Vision
- Data Augmentation
- Medical Image Analysis

## Model Architecture
4-layer CNN with progressive filter scaling (32→64→128→256), BatchNormalization, and Dropout regularization.