# 🚦 SpeedVision: Vehicle Speed Estimation

An AI-powered vehicle speed estimation system using YOLO11, ByteTrack, OpenCV, and Gradio.

## Project Overview

SpeedVision detects vehicles, tracks their movement, and estimates their real-world speed from video footage.

## Technologies Used

- Python
- Google Colab
- YOLO11 - Vehicle Detection
- ByteTrack - Object Tracking
- OpenCV - Computer Vision
- NumPy and Pandas
- Plotly - Data Visualization
- Gradio - Web Interface

## Main Features

- Vehicle detection (cars, motorcycles, buses, and trucks).
- Vehicle tracking with unique IDs.
- Real-world speed estimation in km/h and mph.
- Perspective transformation for road calibration.
- Speed-colored bounding boxes.
- Vehicle movement trails.
- Bird's-eye radar visualization.
- Interactive analytics and CSV reports.
- Gradio web application.

## How to Run

1. Open the notebook in Google Colab.
2. Select Runtime → Change runtime type.
3. Choose a T4 GPU (if available).
4. Run all notebook cells.
5. Upload a video or use the sample video.
6. Calibrate the road using four points.
7. Run the vehicle speed estimation system.

