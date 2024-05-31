# virtual_mouse_by_hand_gestures
# Overview
This project implements a virtual mouse system that allows users to control their computer's mouse functions using hand gestures detected through a webcam. Utilizing computer vision and machine learning techniques, the system tracks hand movements and translates them into mouse actions such as clicking, scrolling, and dragging.
# Features
- Real-time Hand Tracking: Uses OpenCV and Mediapipe to accurately track hand movements in real-time.
- Gesture Recognition: Recognizes various hand gestures for different mouse actions:
- Move Cursor: Control the cursor position with hand movement.
- Left Click: Pinch gesture for left clicking.
- Right Click: Pinch gesture with a different hand configuration for right-clicking.
- Double click: By Double clicking on any file.
- Drag an Drop: Drags and drops the file from one location to another location.
- Scroll: Scroll up and down by moving the hand vertically and also left and right by moving the hand horizontally.
- User-friendly Interface: Simple and intuitive interface for easy interaction.
- Cross-Platform Compatibility: Works on Windows, macOS, and Linux.
# Technologies used
- Python: The core programming language for the project.
- OpenCV: For capturing and processing video frames.
- Mediapipe: For hand tracking and gesture recognition.
- PyAutoGUI: To control the mouse and keyboard operations.
# Setup and run
## Pre-requisites
Python: (3.6 - 3.8.5)

Anaconda Distribution: To download click [here](https://www.anaconda.com/download)

Download and Extract the Project Folder Name Virtual_mouse_by_hand_gestures.

Step 1:
##
    conda create --name gest python=3.8.5
Step 2:
## 
    conda activate gest
Step 3:
##
    pip install -r requirements.txt
Step 4:
## 
    python virtual_mouse_by_hand_gestures.py
# Acknowledgemnts
- The project utilizes [OpenCv](https://opencv.org/) for video processing.
- Hand tracking and gesture recognition are powered by [Mediapipe](https://mediapipe.dev).
- Mouse control is handled using [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/).

# Contact
For any inquiries or feedback please contact smssadak1@gmail.com
		
  
