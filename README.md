# Hand Gesture Mouse Controller 🖐️🖱️

This project uses **MediaPipe**, **OpenCV**, and **PyAutoGUI** to create a gesture-based mouse controller. It enables you to move the mouse, perform clicks (left, right, double-click), and even take screenshots using hand gestures detected via a webcam.

---

## Features ✨
- **Move the Mouse**: Control the mouse pointer using your hand's movements.
- **Left Click**: Perform a left-click gesture.
- **Right Click**: Perform a right-click gesture.
- **Double Click**: Perform a double-click gesture.
- **Take Screenshots**: Capture the screen with a specific gesture.
- Real-time hand tracking and gesture recognition using **MediaPipe Hands**.

---

## How It Works 🛠️
1. **Hand Detection**: The program uses MediaPipe's deep learning model to detect hand landmarks in real-time.
2. **Gesture Recognition**: Specific gestures (e.g., finger angles and distances) trigger actions like clicks or screenshots.
3. **Mouse Control**: Mouse actions (e.g., moving, clicking) are simulated using `pyautogui` and `pynput`.

---

## Installation 🖥️

### Prerequisites
- Python 3.7+
- A webcam
