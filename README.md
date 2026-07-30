# signspeak-real-time-gesture-to-text-audio
AI-powered real-time gesture recognition system that converts sign language into text and speech.

# SignSpeak: Real-Time Gesture to Text and Audio for Speech-Impaired


## Project Overview

**SignSpeak** is an AI-powered real-time gesture recognition system designed to improve communication for speech- and hearing-impaired individuals. The application detects hand gestures using a webcam, recognizes sign language in real time using deep learning and computer vision, and converts the recognized gestures into both text and speech.

The goal of this project is to bridge communication gaps by providing an accessible and user-friendly solution for sign language interpretation.

---

## Problem Statement

Millions of people with speech and hearing impairments face communication challenges in their daily lives because many people do not understand sign language.

SignSpeak addresses this problem by automatically recognizing hand gestures and converting them into readable text and audible speech, making communication more accessible and inclusive.

---

## Features

- Real-time hand gesture detection
- Webcam-based gesture recognition
- Deep learning-based gesture classification
- Converts sign language into text
- Generates audio output from recognized text
- Fast and user-friendly interface
- Easy to run on a local computer

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Libraries & Frameworks
- TensorFlow / Keras
- OpenCV
- MediaPipe
- NumPy
- Scikit-learn
- Pyttsx3

### Model & Tools
- Deep Learning
- Computer Vision
- Hand Landmark Detection

---

## Project Structure

```text
signspeak-real-time-gesture-to-text-audio/

├── src/
│   ├── DAT_INPUT.py
│   ├── Data_input.py
│   ├── Itrain.py
│   ├── Real.py
│   └── scaler.py
│
├── models/
│   ├── SGT.h5
│   └── label_encoder.pkl
│
├── logs/
│   ├── asl_recognition.log
│   └── gesture_detection.log
│
├── output/
│   └── voice_output.mp3
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/signspeak-real-time-gesture-to-text-audio.git
```

### 2. Navigate to the project directory

```bash
cd signspeak-real-time-gesture-to-text-audio
```

### 3. Install the required dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python src/Real.py
```

---

## How It Works

1. Open the application.
2. The webcam captures live hand gestures.
3. MediaPipe detects hand landmarks.
4. The trained deep learning model recognizes the gesture.
5. The recognized gesture is converted into text.
6. The generated text is converted into speech for audio output.

---


## Future Scope

- Support complete sentence recognition
- Add Indian Sign Language (ISL) support
- Improve model accuracy using larger datasets
- Mobile application development
- Multi-language speech output
- Cloud deployment for online accessibility

---

## Author

**Nandini Patil**

B.Tech Artificial Intelligence & Machine Learning Student

---


## Acknowledgements
This project was developed as part of an Artificial Intelligence and Machine Learning learning journey to explore the practical applications of deep learning and computer vision in solving real-world communication challenges.

This project was developed as part of an Artificial Intelligence and Machine Learning learning journey to explore the practical applications of deep learning and computer vision in solving real-world communication challenges.
