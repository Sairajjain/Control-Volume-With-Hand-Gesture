# 🎚 Control Volume with Hand Gestures using Python

A real-time Python application that allows users to control system volume through hand gestures using a webcam. The project uses *OpenCV, **MediaPipe, and **pycaw* to detect hand landmarks and adjust system volume based on the distance between the thumb and index finger.

## 🚀 Features

- Real-time hand tracking with MediaPipe
- Adjust system volume using finger distance
- Dynamic volume bar and percentage display
- FPS (Frames Per Second) display
- Visual feedback using OpenCV drawings

## 📷 Demo

https://github.com/yourusername/control-volume-hand-gesture/assets/demo.gif (You can upload a short screen recording here)

## 🧠 How It Works

1. Captures video feed using OpenCV.
2. Detects hands and landmarks using MediaPipe.
3. Measures the distance between thumb and index finger.
4. Maps that distance to the system volume range using pycaw.
5. Updates volume and GUI indicators in real-time.

## 📦 Dependencies

- Python 3.6+
- OpenCV (cv2)
- NumPy
- MediaPipe
- pycaw
- comtypes

You can install the required packages using:

```bash
pip install opencv-python mediapipe numpy pycaw comtypes
