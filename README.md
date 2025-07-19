🎭 Emotion Detector using CNN
This project is an Emotion Detection System using a Convolutional Neural Network (CNN). It takes input from a webcam or video feed, detects faces using Haar Cascades, and classifies emotions using a pre-trained deep learning model.

🔍 Features
Detects faces in real-time

Classifies facial emotions:

Angry 😠

Disgust 🤢

Fear 😨

Happy 😀

Sad 😢

Surprise 😲

Neutral 😐

Uses OpenCV for face detection and real-time video

Loads pre-trained Keras model for prediction

🧠 Model
Pre-trained model: _mini_XCEPTION.102-0.66.hdf5

Framework: Keras with TensorFlow backend

Haar Cascade used for face detection

🚀 Getting Started
🔧 Prerequisites
Install the required libraries using pip:

bash
Copy
Edit
pip install keras tensorflow opencv-python numpy
Make sure you're using Python 3.10 or later.

📁 Project Structure
nginx
Copy
Edit
Emotion Detector/
├── Emotion_detector.py
├── _mini_XCEPTION.102-0.66.hdf5
└── haarcascade_frontalface_default.xml
▶️ How to Run
Run the following command in your terminal:

bash
Copy
Edit
python Emotion_detector.py
Make sure your webcam is connected — the program will open a video window and show real-time emotion predictions.

🛠 Tech Stack
Python 3.10

Keras

TensorFlow

OpenCV

NumPy

📸 Demo
(Optional: Add screenshots or a demo video link here)



