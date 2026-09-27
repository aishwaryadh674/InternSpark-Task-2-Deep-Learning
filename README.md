# Task 2 - Deep Learning Image Classification

## Project
CIFAR-10 Image Classification using Transfer Learning

## Framework
- PyTorch
- Torchvision

## Model
Pretrained ResNet18 with transfer learning.

## Dataset
CIFAR-10 image classification dataset.

For this project, a subset of:
- 5,000 training images
- 1,000 testing images

was used.

## Requirements
- Python 3
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

## Installation

Run:

python -m pip install torch torchvision matplotlib numpy jupyter

## How to Run

Open Command Prompt in the project folder and run:

python -m notebook

Then open:

task2_deep_learning.ipynb

Run all notebook cells from beginning to end.

## Data Augmentation

The training images use:
- Resize
- Random horizontal flip
- Random rotation
- Normalization

## Evaluation

The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score

Training loss and training accuracy curves are also included in the notebook.

## Saved Model

The trained model is saved as:

cifar10_resnet18.pth

## Project Contents

- task2_deep_learning.ipynb - Training and evaluation notebook
- cifar10_resnet18.pth - Saved trained model
- README.md - Setup and execution instructions