# Comparative-Study-of-Deep-Learning-Models-for-Plant-Disease-Detection
This repository presents a comparative study of three deep learning architectures for automated plant disease classification using the New Plant Diseases Dataset (Augmented). The objective is to evaluate the performance of a custom Convolutional Neural Network against two transfer learning approaches based on ResNet50 and EfficientNetB0.
# Plant Disease Classification using Deep Learning

## Overview
This repository compares three deep learning architectures for plant disease classification using the New Plant Diseases Dataset (Augmented). The project evaluates the performance of a custom CNN, ResNet50, and EfficientNetB0 for multi-class image classification across 38 plant disease categories.

## Models
- Custom CNN (Sequential)
- ResNet50 (Transfer Learning)
- EfficientNetB0 (Transfer Learning)

## Dataset
- New Plant Diseases Dataset (Augmented)
- 54,000+ images
- 38 classes

## Repository Structure
├── Plant_Disease_Detection_ConvNet_Sequential.ipynb

├── Plant_Disease_Detection_ResNet50_TransferLearning.ipynb

├── Plant_Disease_EfficientNetB0.ipynb

└── README.md

## Technologies
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib

## Results
The sequential model produced a baseline validation accuracy of 66%. Using a Resnet model and transfer learning improved this accuracy to almost 96%. Finally, with data engineering and image changes, the validation accuracy improved till 99%. 

