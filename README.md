# Air Canvas — Hand Gesture Drawing App


<br>
<p align="center">
  A real-time hand gesture–controlled virtual drawing system<br>
  built using computer vision and webcam-based hand tracking
</p>

<p align="center">
  <img src="https://cdn.simpleicons.org/python" width="34" alt="Python"/>
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/opencv" width="34" alt="OpenCV"/>
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/mediapipe" width="34" alt="MediaPipe"/>
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/numpy" width="34" alt="NumPy"/>
</p>

<br>

## About the Project

Air Canvas is a computer vision–based virtual drawing application that allows users to draw on a digital canvas using hand gestures captured through a webcam.

Using MediaPipe Hands for real-time hand landmark detection and OpenCV for image processing, the application provides a smooth, touch-free, and interactive drawing experience.

<br>

## Features

- Real-time hand tracking  
- Draw using index finger  
- Change colors using index + middle finger  
- Eraser mode  
- Clear canvas button  
- Live visual feedback  
- Smooth and responsive drawing  

<br>

## Gesture Controls (Animated)

<p align="center">
  <img src="assets/gestures.gif" width="70%" alt="Gesture Controls"/>
</p>

| Gesture | Action |
|-------|--------|
| Index finger | Draw |
| Index + middle finger | Change color |
| Index + middle on CLEAR | Clear canvas |
| Q key | Quit application |

<br>

## Technologies Used

- Python  
- OpenCV  
- MediaPipe Hands  
- NumPy  

<br>

## Project Structure

```text
Air-Canvas/
│
├── main.py
├── requirements.txt
├── assets/
│   ├── air-canvas-demo.gif
│   └── gestures.gif
└── README.md
