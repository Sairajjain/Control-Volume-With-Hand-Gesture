# 🎚️ Volume Control with Hand Gestures Using Python

Control your system’s audio volume in real-time using just hand gestures and a webcam! This project combines **computer vision**, **gesture recognition**, and **system audio control** to provide a seamless, touchless interface for adjusting volume.

---

## 📄 Project Description

**"Volume Control with Hand Gestures"** is an innovative computer vision project developed using Python that enables users to control the system’s audio volume in real-time using only hand gestures and a webcam. The main goal of this project is to explore how natural hand movements can be interpreted through machine learning and computer vision techniques to replace physical input devices.

The system uses **OpenCV** for capturing real-time video and rendering visual feedback, **MediaPipe** for accurate hand and finger landmark detection, and **pycaw** for controlling the system's volume on Windows platforms. The user simply brings their **thumb and index finger closer or farther apart** to decrease or increase the volume respectively. As the distance between the fingers changes, the volume level updates accordingly, and the user is provided with visual cues including a volume bar, percentage, and finger tracking overlay.

This project not only demonstrates how gesture-based control can be effectively implemented but also serves as a foundational prototype for more advanced Human-Computer Interaction (HCI) systems. It can be extended for controlling other functions like brightness, media playback, or even GUI interactions — especially useful in touchless interfaces in public or hygienic environments.

---

## 🔍 Key Highlights

- Real-time hand gesture recognition with MediaPipe's 21-point hand landmark model.
- Converts physical hand movement into volume control without touching the keyboard or mouse.
- Smooth and continuous control with interpolation from finger distance to system audio volume range.
- Live feedback through a volume bar, FPS counter, and highlighted gesture points.
- Modular codebase with separate files for hand tracking (`handtracking.py`) and control logic (`hand.py`).

---

## 👨‍💻 Technologies Used

| Technology | Purpose |
|------------|---------|
| **Python** | Core programming language |
| **OpenCV** | Real-time image processing and visualization |
| **MediaPipe** | Google's framework for detecting hand landmarks |
| **pycaw** | Windows-only library for controlling system audio |
| **NumPy** | For interpolation of gesture distance |

---

## 📸 Screenshots

### ➖ Volume at 0%
![Low Volume](images/low_volume.png)

### ➕ Volume at 100%
![High Volume](images/high_volume.png)

> Make sure these images are inside an `images/` folder in your project directory.

---

## 🔧 How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/volume-control-hand-gestures.git
cd volume-control-hand-gestures
