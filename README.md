# 👁️ Eye Tracking Virtual Mouse

A Python-based virtual mouse that allows users to control the mouse cursor and perform clicks using only their eye movements — no physical mouse required.

This project utilizes **OpenCV**, **MediaPipe**, and **PyAutoGUI** to track the user's eye and move the cursor accordingly. Clicking is triggered by blinking the left eye.

## 🧠 How It Works

- The system uses **MediaPipe's FaceMesh** to detect facial landmarks in real-time.
- Tracks landmarks around the **right eye** to move the mouse cursor.
- Detects **blink gestures** from the **left eye** to simulate mouse clicks.
- The camera input is mirrored for a natural experience.

## 🖥️ Features

- 👀 Real-time eye movement tracking
- 🖱️ Eye blink to click
- 🧠 AI-based landmark detection using MediaPipe
- ⚡ Lightweight and fast

## 📦 Requirements

Install the following Python packages before running the project:

```bash
pip install opencv-python mediapipe pyautogui
