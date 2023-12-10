# Forgery Detection Model

This repository contains a Convolutional Neural Network (CNN) model for forgery detection, trained on the CASIA 2.0 dataset. The model is implemented using PyTorch and torchvision.


## Testing Accuracy
![image](https://github.com/partho2001/forgery_detection/assets/42618752/8661b2f4-2b22-4593-bebf-b82e49dd012f)

## Requirements

- Python 3
- PyTorch
- torchvision
- torch

## Dataset

CASIA 2.0 is used 
https://www.kaggle.com/datasets/divg07/casia-20-image-tampering-detection-dataset/code

## Model Architecture
The forgery detection model consists of a simple CNN with two convolutional layers followed by two fully connected layers.

Input: Grayscale images of size 32x32
Output: Binary classification (forged or authentic)

## Training
The model is trained using the Adam optimizer with a cross-entropy loss function. Training takes place over several epochs on a subset of the CASIA 2.0 dataset.

## Evaluation
After training, the model is evaluated on a test set to measure its accuracy.
![image](https://github.com/partho2001/forgery_detection/assets/42618752/8661b2f4-2b22-4593-bebf-b82e49dd012f)
