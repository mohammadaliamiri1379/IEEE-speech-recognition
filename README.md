# IEEE-speech-recognition

## Overview

This project is aimed at building a machine learning model for classifying robot-generated voices into five different categories. The goal is to distinguish between various types of robot voices based on audio data.

## Dataset

The dataset used for training and evaluation consists of audio recordings of robot voices. Each voice belongs to one of the following five categories:

1. Category 0
2. Category 1
3. Category 2
4. Category 3
5. Category 4

## Model Architecture

The machine learning model employed for this classification task is a Convolutional Neural Network (CNN). The model architecture includes multiple convolutional layers followed by max-pooling, batch normalization, and dropout layers to prevent overfitting. The final layer utilizes a softmax activation function to output probabilities for each category.

## Requirements

To run this project, you will need the following:

- TensorFlow/Keras (for deep learning)
- NumPy (for numerical operations)
- Matplotlib (for plotting spectrograms)
- PyDub (for audio processing)
- Jupyter Notebook (optional, for running code cells interactively)
##Resukts
  We manged to achieve 85% accuracy based on unseen data of IEEE competition.
