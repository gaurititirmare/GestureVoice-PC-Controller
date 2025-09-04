# smart-gesture-voice-PC_controller

Smart Gesture and Voice PC_Controller is an AI-powered interface that allows users to control their computer using hand gestures and voice commands, eliminating the need for physical input devices. With modes for mouse and keyboard control, users can navigate the screen, click, and type with gestures or dictate text using speech. This system integrates computer vision and speech recognition, providing an intuitive, touchless experience ideal for accessibility and smart environments.



## 1. Organize Your Project Directory
Structure your project like this:

![image](https://github.com/user-attachments/assets/3e9b2df8-7156-4919-9177-4044d86a35af)


--- 


# Steps to Run the Project
## 1. Clone or Download the Project
If it's on GitHub, clone it:

## 2. Install Required Dependencies
Make sure requirements.txt is present, then run:

- pip install -r requirements.txt

## 3. Run the Project
Use this command to start the main interface:

- python main.py


## ✨ Features

- Gesture-based **mouse control** using index and thumb detection.
- Gesture-based **virtual keyboard** with real-time typing.
- **Voice commands** for mode switching, opening apps, searching web, and more.
- **Speech-to-text dictation** using Google's API.
- Simple **GUI menu** to select control mode.

## 🧠 Technologies Used

- OpenCV & MediaPipe – Hand detection and tracking
- SpeechRecognition – Voice input and command recognition
- PyAutoGUI – Mouse and keyboard emulation
- Tkinter – Menu UI
- Numpy, threading, Pynput, subprocess, etc.

