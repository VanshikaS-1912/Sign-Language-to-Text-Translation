# Sign Language to Text Translation (Indian Sign Language – ISL)

This project enables real-time translation of **Indian Sign Language (ISL)** gestures into text using deep learning and computer vision. It aims to support seamless communication for individuals with hearing and speech impairments.

---

## Features
- Real-time gesture recognition through webcam
- Deep learning model trained on ISL gesture dataset
- Converts gestures into readable English text
- Designed for assistive accessibility solutions

---

## Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Deep Learning | TensorFlow / Keras |
| Computer Vision | OpenCV |
| Pose Detection | MediaPipe |
| Data Structures | NumPy |
| Model | `.h5` trained model |

---

## Project Structure
Sign-Language-to-Text-Translation/
│
├── MP_Data/ # Dataset (MediaPipe keypoints)
├── 30_actions.h5 # Trained gesture recognition model
├── Action Detection Refined.ipynb # Model training & testing notebook
├── LICENSE
└── README.md
