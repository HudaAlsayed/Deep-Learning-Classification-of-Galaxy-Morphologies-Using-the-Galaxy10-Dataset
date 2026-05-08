# Deep-Learning-Classification-of-Galaxy-Morphologies-Using-the-Galaxy10-Dataset
Developed a deep learning pipeline for galaxy morphology classification using CNNs and the Galaxy10 dataset. Applied data augmentation, stratified sampling, and preprocessing techniques to handle class imbalance, achieving 84% test accuracy with a web-based interface for image upload and prediction.

Overview

This project focuses on classifying galaxy morphologies using Deep Convolutional Neural Networks (CNNs) and the Galaxy10 dataset. The system automates galaxy classification into 10 morphological categories, helping address the challenges of analyzing large astronomical datasets manually.

The project includes:

Data preprocessing and augmentation
CNN model training and evaluation
Handling class imbalance
Performance visualization using confusion matrices
A simple web-based interface for image upload and prediction

Features

Galaxy image classification using CNNs
Data augmentation for improved generalization
Stratified train-test splitting
Z-score image standardization
Confusion matrix performance analysis
Web interface for galaxy image prediction
Deep learning pipeline using TensorFlow/Keras

Dataset

The project uses the Galaxy10 Dataset, which contains:

21,785 RGB galaxy images
Image size: 69×69×3
10 galaxy morphology classes
Technologies Used
Python
TensorFlow / Keras
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
Model Architecture

The CNN model consists of:

Convolutional Layers (Conv2D)
ReLU Activation Functions
Max Pooling Layers
Fully Connected Dense Layers
Softmax Output Layer

The model was trained using:

Adam Optimizer
Categorical Cross-Entropy Loss
50 Training Epochs
Workflow
Load and analyze the Galaxy10 dataset
Perform exploratory data analysis (EDA)
Preprocess and standardize images
Apply data augmentation techniques
Train the CNN model
Evaluate performance using accuracy and confusion matrices
Test predictions through the web interface
Results
Achieved 84% test accuracy
Successfully handled class imbalance using:
Stratified sampling
Data augmentation
Identified difficult galaxy classes using confusion matrix analysis
User Interface

The project includes a simple web-based interface where users can:

Upload galaxy images
Simulate galaxy morphology prediction
View predicted class labels
Future Improvements
Apply transfer learning models such as ResNet or VGG
Improve minority class performance using SMOTE or class weighting
Deploy the model as a real-time web application
Enhance UI/UX design and prediction visualization
