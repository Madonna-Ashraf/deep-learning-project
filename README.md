# deep-learning-project
#Problem Description
This project focuses on Brain Tumor Classification using Deep Learning techniques. The model classifies MRI brain images into four categories:
Glioma Tumor
Meningioma Tumor
Pituitary Tumor
No Tumor
A DenseNet-based Convolutional Neural Network (CNN) was implemented using PyTorch to automatically extract features from MRI images and perform accurate classification.
The project also includes multiple experiments.
#Dataset Link
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
#Results
| Experiment       | Test Accuracy |
|------------------|---------------|
| simple densetnet | 63.25%        |
| densenet121      | 93.38%        |
#Instructions for Running the Project
Download the file project and Install Required Libraries
```
import torch
import torch.nn as nn
import torch.optim as optim
from torchvision import datasets,transforms
from torch.utils.data import DataLoader
import matplotlib.pyplot as plt
```
