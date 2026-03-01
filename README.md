# Face Recognition System using CNN (LeNet)

## Overview
A face recognition pipeline built using OpenCV for face detection and a Convolutional Neural Network (LeNet architecture) for multi-class classification.

## Pipeline
1. Face Detection using Haar Cascade
2. Preprocessing (grayscale, histogram equalization, normalization)
3. Label encoding + one-hot encoding
4. CNN model training
5. Evaluation using accuracy, confusion matrix, classification report

## Model Architecture
Conv2D → ReLU → MaxPooling  
Conv2D → ReLU → MaxPooling  
Flatten → Dense → Softmax  

## Results
- Dataset Size: 399 images
- Number of Classes: 4
- Validation Accuracy: 99%
- Macro F1-Score: 0.99
- Optimizer: Adam
- Loss Function: Categorical Cross-Entropy

## Tech Stack
Python, TensorFlow/Keras, OpenCV, NumPy, Scikit-learn, Matplotlib

## How to Run
pip install -r requirements.txt
python src/train.py

## Future Improvements
- Replace Haar Cascade with MTCNN
- Use transfer learning (ResNet/VGGFace)
- Deploy using Flask
