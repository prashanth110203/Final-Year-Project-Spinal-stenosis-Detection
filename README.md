# 🏥 Spinal Vision: CNN-Driven Techniques for Accurate Stenosis Detection Using Deep Learning

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

## 💻 Usage

### Training the Model
```bash
jupyter notebook
# Navigate to notebooks and run training notebook
Running the Deployment Application
Bash

cd "SPINAL STONOSIS/Deployment/Project"
python app.py
Access the application at: http://localhost:5000

📊 Model Performance
Metric	Score
Training Accuracy	95.2%
Validation Accuracy	92.8%
Precision	91.5%
Recall	90.3%
F1-Score	90.9%
Note: Update these values with your actual results

🎓 Features
✅ Automated spinal stenosis detection
✅ Multi-class classification support
✅ Real-time prediction interface
✅ High accuracy CNN model
✅ User-friendly web deployment
✅ Comprehensive visualization tools

🔍 Model Architecture Details
Input Layer: Image preprocessing and augmentation
Convolutional Layers: Feature extraction with ReLU activation
Pooling Layers: Dimensionality reduction
Fully Connected Layers: Classification
Output Layer: Softmax activation for multi-class prediction
👨‍💻 Authors
Prashanth & Kathiravan

GitHub: @prashanth110203
Project: Final Year Project
🙏 Acknowledgments
Medical imaging dataset providers
Project supervisor and guide
TensorFlow and Keras communities
📝 License
This project is developed for academic purposes as part of a final year project.

🔮 Future Enhancements
 Real-time video analysis
 Mobile application deployment
 Integration with hospital management systems
 Multi-modal imaging support
 Explainable AI features (Grad-CAM)
📞 Support
For queries or contributions, please open an issue on GitHub.
