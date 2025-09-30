# air--canvas

## Virtual Paint using Hand Tracking

A real-time computer vision application that enables users to paint virtually using only hand gestures.
This project leverages OpenCV for rendering, MediaPipe for precise hand landmark detection, and NumPy for efficient image operations.

## 🚀 Overview

This application transforms your index finger into a paintbrush and allows you to draw on a digital canvas in real time.
The system detects hand gestures through a webcam feed and maps finger positions into drawing actions.

Gesture-based Drawing → Index finger acts as the brush.

Thumb + Finger Gesture → Start a new stroke.

On-screen Palette → Select colors or clear the canvas.

Live Dual Windows →

Webcam feed (Output) with overlaid strokes

Canvas (Paint) for the final drawing

## 🛠️ Technology Stack
Component	Purpose
Python 3.x	Core programming language
OpenCV	Video capture, image rendering, UI windows
MediaPipe	Hand landmark detection (real-time)
NumPy	Numerical operations and array handling
Deque	Efficient storage of drawing points

## ⚙️ Installation

1. Clone Repository
git clone https://github.com/your-username/virtual-paint-hand-tracking.git
cd virtual-paint-hand-tracking

## 2. Install Dependencies
pip install opencv-python mediapipe numpy

3. Run Application
python virtual_paint.py

## 🎮 Usage Instructions

Select Color: Hover your index finger over one of the color boxes (Blue, Green, Red, Yellow).

Draw: Move your index finger on the screen.

Clear Canvas: Hover finger over the CLEAR box.

Start New Stroke: Bring thumb close to index finger.

Exit: Press Q.

## 🔮 Future Roadmap

 Adjustable brush size

 Extended color palette with HSV color picker

 Save drawings to file (PNG/JPEG)

 Eraser tool with gesture control

 Multi-hand support for collaborative drawing

 Mobile app integration

## 🤝 Contribution Guidelines

Contributions are welcome!

Fork the repository

Create a feature branch (git checkout -b feature-name)

Commit changes (git commit -m "Add feature")

Push to branch (git push origin feature-name)

Create a Pull Request

Please ensure your code follows PEP8 standards and includes proper comments.
