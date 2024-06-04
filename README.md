# Overview
Saqr is a real-time license plate recognition system designed to detect stolen or wanted cars. Utilizing a YOLOv8 model deployed on a Raspberry Pi with a camera, the system captures live video feeds and accurately recognizes license plates. This project supports both Arabic and English characters, making it particularly suitable for Saudi plates.

# Features
- Real-time License Plate Detection: Capture and process live video feeds to detect license plates.
- Character Recognition: Recognize license plates with both Arabic and English characters.
- Data Management: Register, view, and remove license plates from the database.
- Detection Logging: Log detected license plates with timestamp and location.
- Web Interface: User-friendly interface built with Streamlit for easy interaction and manageme.

# Requirements
# System Packages
- libgl1: OpenGL library used by OpenCV.

# Python Packages

- matplotlib==3.8.4
- numpy==1.24.3
- opencv_python_headless==4.9.0.80
- pandas==2.2.2
- Requests==2.32.2
- streamlit==1.35.0
- tensorflow==2.16.1
- torch==2.3.0
- ultralytics==8.2.22
