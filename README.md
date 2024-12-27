# Vehicle-speed-detection-using-Yolov8

This project uses YOLOv8 object detection and a tracking algorithm to monitor vehicle movement and calculate their speed based on frame processing.

## Features
- Detects vehicles in video streams.
- Tracks vehicles moving up and down predefined lanes.
- Calculates and displays the speed of each detected vehicle in kilometers per hour (Km/h).
- Differentiates vehicles moving in different directions.

## Requirements
To run the project, ensure the following dependencies are installed:
- Python
- OpenCV
- Pandas
- NumPy
- [Ultralytics YOLO](https://github.com/ultralytics/yolov8)

You can install the required Python libraries using:
```bash
pip install -r requirements.txt
