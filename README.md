**🚦 Traffic Light Violation Detection System using YOLOv10-S**

A real-time traffic light violation detection system built using YOLOv10-S, a state-of-the-art object detection model. This project detects vehicles and traffic lights from video streams, determines traffic signal status, and automatically identifies vehicles that cross an intersection during a red light.

The system is designed for smart city surveillance, helping reduce manual enforcement, improve road safety, and increase detection accuracy.

**📌 Project Overview**

With the rapid growth of urban traffic, traffic rule violations—especially red-light violations—have become a major safety concern. Traditional manual monitoring using CCTV footage is:

-->Time-consuming

-->Error-prone

-->Difficult to scale

This project solves these issues using a computer-vision-based automated monitoring system that:

-->Detects vehicles and traffic lights

-->Tracks vehicle movement across intersections

-->Identifies red-light violations

-->Logs violation evidence automatically

🧠 Model & Dataset

>Model Used: YOLOv10-S (real-time object detection)

>Dataset: COCO 2017 (filtered subset)

>Classes Used:

Traffic Light

Car

Bus

Truck

Motorcycle

Only a task-specific subset of the COCO dataset was used to improve detection performance for traffic surveillance.

⚙️ System Workflow

Video Input / Camera Feed

Object Detection using YOLOv10-S

Traffic Light State Detection (Red / Green)

Vehicle Tracking using Bounding Boxes

Virtual Stop-Line Rule Evaluation

Red Light Violation Detection

Event Logging with Timestamp & Proof Frame

📊 Evaluation Metrics

The system performance is evaluated using:

mAP (50–95) – Detection accuracy

F1-Score – Balance between precision & recall

Inference Latency – Real-time processing speed

The model achieves high accuracy with real-time performance, making it suitable for live surveillance systems.

🚀 Features

✅ Real-time vehicle and traffic light detection
✅ Automated red-light violation identification
✅ Pre-trained YOLOv10-S integration
✅ Bounding box tracking
✅ Event-based violation logging
✅ Smart city surveillance compatibility
✅ Reduced need for physical enforcement

🛠️ Tech Stack

Programming Language: Python

Framework: Ultralytics YOLO

Computer Vision: OpenCV

Data Handling: Pandas

Model: YOLOv10-S

Dataset: COCO 2017

Tracking: Custom Bounding Box Tracker
