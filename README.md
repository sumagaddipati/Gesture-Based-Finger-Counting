**Gesture-Based Finger Counting Using OpenCV & MediaPipe**

Count the number of fingers raised in real time using hand gestures! This project leverages OpenCV and MediaPipe Hands to detect and count fingers accurately.

**Features**

✅ Real-time hand tracking using MediaPipe

✅ Detects and counts the number of raised fingers

✅ Works smoothly with webcams

✅ Simple and efficient algorithm

**Tech Stack**

Python 🐍

OpenCV 🎥

MediaPipe 🖐

**Demo**

![Screenshot 2025-02-23 110946](https://github.com/user-attachments/assets/79a503a0-2dd7-4f12-8bfc-30b68079440f)

**Installation**

1️⃣ Install dependencies:

pip install opencv-python mediapipe numpy

2️⃣ Run the script:

python finger_counting.py

**Usage**

Show your hand in front of the webcam ✋

The script detects and displays the number of fingers raised

Press 'q' to exit

**Code Overview**

The script captures video from the webcam and uses MediaPipe Hands to detect hand landmarks. It then checks the position of each finger to determine whether it is raised or folded, and counts the number of raised fingers.

**Key Functions:**

Hand Tracking: Uses MediaPipe to detect hand landmarks in real-time.

Finger Status Detection: Determines whether each finger is up or down.

Finger Counting: Counts the number of fingers raised and displays the result.

Real-Time Display: Continuously updates the count based on hand gestures.

**Contribute**

Feel free to fork and improve the project! 🎉


