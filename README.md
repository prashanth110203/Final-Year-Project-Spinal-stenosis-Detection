# Spinal Vision: CNN-Driven Techniques for Accurate Stenosis Detection Using Deep Learning

## 📋 Project Overview

This project implements a deep learning-based system for automatic detection and classification of spinal stenosis from medical imaging data. Using Convolutional Neural Networks (CNN), the system aims to assist medical professionals in early and accurate diagnosis of spinal stenosis conditions.

## 🎯 Objectives

- Develop an automated spinal stenosis detection system using deep learning
- Achieve high accuracy in classification of stenosis severity levels
- Provide a user-friendly deployment interface for medical practitioners
- Reduce diagnosis time and improve detection accuracy compared to manual methods

## 🔬 Methodology

### Dataset
- Medical imaging dataset containing spinal MRI/CT scans
- Preprocessing includes image normalization, augmentation, and resizing
- Multi-class classification (Normal, Mild, Moderate, Severe stenosis)

### Model Architecture
- **Base Model**: Convolutional Neural Network (CNN)
- **Framework**: TensorFlow/Keras
- **Techniques Used**:
  - Transfer Learning
  - Data Augmentation
  - Dropout for regularization
  - Batch Normalization

### Training
- Optimizer: Adam
- Loss Function: Categorical Cross-entropy
- Metrics: Accuracy, Precision, Recall, F1-Score
- Validation Strategy: Train-Test Split / K-Fold Cross Validation

## 🛠️ Technologies Used

- **Programming Language**: Python 3.x
- **Deep Learning**: TensorFlow, Keras
- **Data Processing**: NumPy, Pandas, OpenCV
- **Visualization**: Matplotlib, Seaborn
- **Deployment**: Flask/Streamlit
- **Development Environment**: Jupyter Notebook

## 📁 Project Structure
Final Year Project/
│
├── SPINAL STONOSIS/
│ ├── .ipynb_checkpoints/
│ ├── Deployment/
│ │ └── Project/
│ │ ├── venv/ # Virtual environment (not in repo)
│ │ ├── app.py # Flask/Streamlit deployment app
│ │ ├── model.h5 # Trained model file
│ │ └── static/ # Web assets (CSS, JS, images)
│ │
│ ├── data/ # Dataset directory
│ ├── models/ # Saved model checkpoints
│ ├── notebooks/ # Jupyter notebooks
│ │ ├── data_exploration.ipynb
│ │ ├── model_training.ipynb
│ │ └── evaluation.ipynb
│ └── src/ # Source code
│ ├── preprocessing.py
│ ├── model.py
│ └── utils.py
│
├── requirements.txt # Python dependencies
├── .gitignore
└── README.md # This file
