# Color Object Detection

A simple computer vision project that detects red-colored objects in real-time using the webcam.

## Requirements
- Python 3
- OpenCV
- numpy

Install:
pip install opencv-python numpy

## Run:
python color_detection.py

## How it works:
- Converts each frame from BGR to HSV.
- Segments red regions using two HSV ranges.
- Finds contours and highlights detected objects.
