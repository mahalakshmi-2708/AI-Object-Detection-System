
# AI Object Detection System

## Overview

AI Object Detection System is a web-based application developed using Flask and YOLOv8. The system can detect and identify objects from images, videos, and live webcam streams in real time.

The project uses the YOLOv8 (You Only Look Once) deep learning model to perform fast and accurate object detection.

## Features

* Image Object Detection
* Video Object Detection
* Real-Time Webcam Detection
* Detection Summary with Object Counts
* Crowd Alert System
* User-Friendly Web Interface
* YOLOv8 Powered Detection

## Technologies Used

* Python
* Flask
* YOLOv8 (Ultralytics)
* OpenCV
* HTML
* CSS
* JavaScript

## Project Structure

ObjectDetectionProject/

├── static/

│   ├── outputs/

│   └── style.css

├── templates/

│   ├── home.html

│   ├── image.html

│   ├── video.html

│   └── webcam.html

├── uploads/

├── app.py

├── requirements.txt

├── .gitignore

└── README.md

## Installation and Setup

### Step 1: Clone Repository

git clone YOUR_GITHUB_REPOSITORY_URL

cd ObjectDetectionProject

### Step 2: Create Virtual Environment

Windows:

python -m venv venv

### Step 3: Activate Virtual Environment

Windows PowerShell:

venv\Scripts\Activate.ps1

### Step 4: Install Required Libraries

pip install -r requirements.txt

### Step 5: Run Application

python app.py

### Step 6: Open Browser

http://127.0.0.1:5000

## How to Use

### Image Detection

1. Open the application.
2. Click on Image Detection.
3. Upload an image.
4. Click Detect Objects.
5. View detected image and object counts.

### Video Detection

1. Open Video Detection.
2. Upload a video file.
3. Click Detect Objects.
4. Wait for processing.
5. View the detected video output.

### Webcam Detection

1. Open Webcam Detection.
2. Allow camera permission.
3. Start webcam.
4. View real-time object detection.

## Crowd Alert Feature

The system generates an alert when multiple persons are detected in a frame.

Example:

⚠ Crowd Alert Detected!

## YOLOv8 Model

This project uses the YOLOv8 Nano model:

yolov8n.pt

Advantages:

* Fast inference speed
* Lightweight model
* Suitable for real-time applications
* Low hardware requirements

## Future Enhancements

* Face Recognition Integration
* Vehicle Number Plate Detection
* AI Surveillance Dashboard
* Cloud Deployment
* Mobile Application Support
* Advanced Analytics

## Results

The system successfully detects common objects such as:

* Person
* Car
* Bus
* Truck
* Bicycle
* Motorcycle
* Dog
* Cat

and many more classes supported by YOLOv8.

## Author

Mahalakshmi Velisetti

## License

This project is developed for educational and learning purposes.
