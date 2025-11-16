AI Face Emotion Detection

This project is an AI-powered Emotion Detection System that uses deep learning to recognize human facial expressions from images or video streams. The model analyzes facial features and predicts emotions such as Happy, Sad, Angry, Surprise, Neutral, Fear, and Disgust using a trained Convolutional Neural Network (CNN).

✨ Project Overview

The system takes a human face as input, processes it using image preprocessing techniques, and classifies the detected emotion. It is built using Python, TensorFlow/Keras, and OpenCV, making it fast, efficient, and easy to deploy.

🎯 Features

Detects emotions from images or webcam in real-time

Uses a deep learning CNN model

Pretrained on the FER2013 dataset

Supports seven common facial emotions

Lightweight and optimized for high accuracy

Easy to integrate with other applications

🧠 Model Architecture

Conv2D layers for feature extraction

MaxPooling to reduce spatial size

Batch Normalization to stabilize learning

Dropout to prevent overfitting

Dense layers for classification

Softmax output layer for emotion prediction

🛠️ Technologies Used

Python

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

ImageDataGenerator for data augmentation

🚀 How It Works

System loads the trained CNN model

Detects the face using OpenCV's Haar Cascade

Preprocesses the face into 48x48 grayscale

Model predicts the emotion class

Displays emotion label on the face live

📂 Folder Structure
📁 AI-Emotion-Detection
 ├── 📁 dataset
 ├── 📁 model
 ├── 📁 scripts
 ├── 📁 images
 ├── train.py
 ├── detect.py
 ├── requirements.txt
 └── README.md

📈 Accuracy

The model achieves good accuracy on the FER2013 dataset thanks to data augmentation, dropout layers, and batch normalization.

📝 Future Improvements

Add support for multi-face detection

Deploy as a mobile app

Convert to TensorFlow Lite

Use MobileNetV2 for faster inference
