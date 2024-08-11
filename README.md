# Traffic Monitoring with YOLOv8 and ByteTrack
![](demo/output.gif)

## Project Overview

**Traffic Monitoring with YOLOv8 and ByteTrack** 
is a real-time traffic surveillance system designed to monitor and track vehicles using advanced computer vision techniques.
This project leverages the YOLOv8 object detection model for identifying vehicles and ByteTrack for robust multi-object tracking.

## Why This Project?

Traffic monitoring is crucial for understanding traffic patterns, managing congestion, and ensuring road safety. 
Traditional methods can be cumbersome and inefficient. By utilizing state-of-the-art computer vision models like YOLOv8 and ByteTrack, 
this project aims to provide a more accurate, efficient, and scalable solution for real-time traffic analysis.

## What This Project Does

1. **Vehicle Detection**: Utilizes YOLOv8 to detect vehicles in video streams or images with high accuracy.
2. **Vehicle Tracking**: Employs ByteTrack for tracking multiple vehicles across frames to maintain identity consistency.
3. **Real-Time Processing**: Designed to work in real-time for continuous traffic monitoring.

## How It Works

1. **Input**: The system takes video input from a file or live camera feed.
2. **Detection**: YOLOv8 processes each frame to identify vehicles and other objects.
3. **Tracking**: ByteTrack tracks the detected vehicles across frames to ensure continuous monitoring.
4. **Traffic Analysis**: Based on the tracked vehicles, the system can perform various traffic analysis tasks, including vehicle counting, speed estimation
5. **Output**: The system provides visual annotations on the video feed, including bounding boxes and tracking IDs.

## Installation and Setup

### Prerequisites

- Python 3.8 or higher
- Pip (Python package installer)
- Supervison Library
- Ultralytics Library
- Opencv Library

### Installation Steps

**Clone the Repository**

   ```bash
git clone https://github.com/Milad0310/Traffic-Monitoring-YOLOv8-and-ByteTrack.git
   ```

 ```bash
cd traffic-monitoring-yolo-v8-bytetrack
   ```

```bash
pip install -r requirements.txt 
   ```
