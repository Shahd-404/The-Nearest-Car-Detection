# Nearest Car Detection Project


This project implements a system to detect and identify the nearest car within a video frame using computer vision techniques.

## Project Overview

* **Purpose:** Detect and identify the nearest car in a video and provide audio alerts based on proximity.
* **Technologies Used:**
    * Python
    * PyTorch
    * OpenCV
    * YOLOv5 (pre-trained object detection model)
    * gtts (optional: for text-to-speech audio alerts)
* **Functionality:**
    * Processes video frames to detect cars using YOLOv5.
    * Calculates the distance to the closest detected car based on its bounding box width.
    * Provides visual cues (bounding box and distance overlay on the video frame).
    * Optionally plays audio alerts when a car is within a predefined distance threshold (e.g., 10 meters, 5 meters).

## Installation

**Prerequisites:**

* Python 3.x with necessary libraries (PyTorch, OpenCV, etc.) installed. Refer to official documentation for installation instructions.
* A YOLOv5 model (e.g., `yolov5s`) downloaded. Installation instructions can be found at https://github.com/ultralytics/yolov5.

**Installing Dependencies:**

```bash
pip install torch torchvision opencv-python gtts (optional for audio alerts)

