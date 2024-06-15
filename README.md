# Real-Time Face Detection using OpenCV

This Python script demonstrates real-time face detection using OpenCV (cv2). It captures video from the webcam, detects faces, and draws rectangles around them on the video stream.

## Overview

The script utilizes Haar cascades provided by OpenCV to detect faces and full bodies in the video feed. It converts the webcam frames to grayscale, applies face detection using the pre-trained cascade classifier, and displays the video with annotated face rectangles.

## Features

- **Real-Time Face Detection**: Detects faces from a live webcam feed.
- **Haar Cascades**: Uses pre-trained Haar cascades for face and full body detection.
- **OpenCV Integration**: Utilizes OpenCV library for computer vision tasks.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
2. **Install OpenCV:**
    Ensure you have OpenCV installed in your Python environment. You can install it via pip:
    pip install opencv-python
3.**Run the Script:**
   python face_detection.py
   
**Instructions:**

-The script will open your webcam and start detecting faces in real-time.
-Detected faces will be highlighted with rectangles on the video feed.
-Press 'q' to exit the application.
   
