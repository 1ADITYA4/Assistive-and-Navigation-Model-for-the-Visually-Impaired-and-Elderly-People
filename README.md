# 🧭 Assistive Object Detection & Navigation System for the Visually Impaired

An AI-powered, voice-interactive system built with computer vision and speech recognition to help visually impaired individuals navigate and identify everyday objects in real-time.

![YOLO + Voice Interaction](https://img.shields.io/badge/Python-3.8%2B-blue)
![YOLOv8](https://img.shields.io/badge/Object%20Detection-YOLOv8-green)
![Voice](https://img.shields.io/badge/Voice%20Command-Enabled-orange)
![Status](https://img.shields.io/badge/Project-Active-lightgreen)

---

## 📌 Overview

This project leverages **YOLOv8**, **OpenCV**, and voice interaction to assist users in identifying objects and safely navigating their environment. It offers **real-time detection, distance estimation**, and **audio-based navigation**, making it especially helpful for **visually impaired or elderly users**.

---

## 🎯 Key Features

✅ **🎙️ Object Selection via Voice**  
Speak naturally to choose the object you want to locate (e.g., "laptop", "bottle").

✅ **🔍 Real-Time Detection & Tracking**  
Uses **YOLOv8** to detect and track objects across video frames.

✅ **📏 Distance & Direction Awareness**  
Calculates the distance and gives clear instructions like "Go straight", "Turn left", or "Object to your right".

✅ **🗣️ Interactive Voice Feedback**  
Provides spoken guidance using text-to-speech.

✅ **🧠 Smart Multi-threading**  
Speech and video detection run in sync without lag using Python’s threading module.

✅ **💾 Save Video Frames**  
Capture and store video frames for review/debugging.

✅ **🌐 Cross-Platform Compatibility**  
Runs on any OS supporting Python 3.8+, with no external hardware required.

---

## ⚙️ How It Works

### 🔎 Object Detection
YOLOv8 detects objects from the video stream using a pre-trained model.

### 📐 Distance Estimation
Calculates the distance of the selected object using its size in pixels and known camera focal length.

### 🧭 Directional Navigation
Determines the direction (left/right/straight) to guide the user toward the object.

### 🧑‍💻 Voice Interaction
- Accepts voice commands via microphone.
- Speaks navigation instructions using text-to-speech.

---

## 🧪 Use Cases

- **Identify personal belongings** like phones, wallets, or keys.  
- **Navigate indoor spaces** safely—e.g., locating a chair or door.  
- **Guide elderly users** around home environments.  
- Ideal for **assistive robotics or wearables**.

---

## 🧰 Tech Stack

| Component             | Technology                  |
|----------------------|-----------------------------|
| Language             | Python                      |
| Object Detection     | YOLOv8 via Ultralytics      |
| Image Processing     | OpenCV (`cv2`)              |
| Speech Recognition   | `speech_recognition`        |
| Text-to-Speech       | `pyttsx3`                   |
| Multithreading       | Python `threading`          |

---

## 🚀 Getting Started

### 🔧 Prerequisites

Make sure you have Python 3.8+ installed.

Install dependencies:
```bash
pip install ultralytics opencv-python speechrecognition pyttsx3

