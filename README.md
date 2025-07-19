# 🎭 Emotion Detector using CNN

This project is an **Emotion Detection System** using a Convolutional Neural Network (CNN).  
It takes input from a webcam, detects faces using Haar Cascades, and classifies emotions using a pre-trained deep learning model.

---

## 🔍 Features

- Detects faces in real-time using OpenCV
- Classifies facial emotions:
  - 😠 Angry  
  - 🤢 Disgust  
  - 😨 Fear  
  - 😀 Happy  
  - 😢 Sad  
  - 😲 Surprise  
  - 😐 Neutral
- Real-time video stream from webcam
- Loads a pre-trained Keras model for accurate predictions

---

## 🧠 Model Details

- **Pre-trained Model:** `_mini_XCEPTION.102-0.66.hdf5`
- **Framework:** Keras (with TensorFlow backend)
- **Face Detection:** Haar Cascade Classifier (`haarcascade_frontalface_default.xml`)

---

## 🚀 Getting Started

### 🔧 Prerequisites

Make sure Python **3.10** is installed.

Install required libraries:

```bash
pip install keras tensorflow opencv-python numpy
