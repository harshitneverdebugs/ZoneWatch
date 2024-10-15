# Project Title: Video Object Detection and Annotation with YOLOv5, YOLOv8, and Detectron2

## Overview
This project demonstrates the use of state-of-the-art object detection models, including YOLOv5, YOLOv8, and Detectron2, along with supervision for video frame annotation. The project processes videos from various environments, annotates detected objects with bounding boxes and labels, and applies custom polygon zones for advanced video analysis.

## Features
- **YOLOv5 Integration**: Utilize the YOLOv5 model for object detection and annotation within video frames.
- **YOLOv8 Integration**: Detect objects using the latest YOLOv8 model with additional features for accuracy and flexibility.
- **Detectron2 Integration**: Detect objects and perform instance segmentation using the Detectron2 framework.
- **Supervision Library**: Annotate bounding boxes and labels for detected objects, as well as handle video frames and apply polygon zones.
- **Video Frame Processing**: Extract, process, and visualize frames from videos, with detection results displayed on the frames.
- **Custom Zone Triggering**: Define and monitor polygonal zones in video frames, triggering actions based on object presence within the zone.

## Models and Libraries Used
- **YOLOv5**: A popular and high-performance object detection model that is fast and accurate for real-time applications.
- **YOLOv8**: The latest version of YOLO, providing improvements in speed and precision for object detection tasks.
- **Detectron2**: A flexible, high-performance framework for object detection, instance segmentation, and other tasks.
- **Supervision Library**: A library to assist with video annotation, including bounding box creation and zone monitoring.

## Video Assets
The project processes video files from various environments, including:
- **Market Square**
- **Grocery Store**
- **Subway Station**

These videos are used to demonstrate object detection in real-world scenarios.

## Output
The processed video frames are displayed with annotations, including:
- Detected objects with bounding boxes and class labels.
- Custom polygon zones where detections trigger specific annotations.

Additionally, videos with annotations are saved to the output directory, allowing for further analysis and presentation.

## Conclusion
This project offers a comprehensive approach to object detection in videos using YOLOv5, YOLOv8, and Detectron2 models. By leveraging the Supervision library, it enhances the visual analysis of detected objects, providing a valuable tool for real-time detection and monitoring.

## Project Setup

### Prerequisites
- Python 3.8+
- NVIDIA GPU with CUDA support
- Installed Python packages from `requirements.txt`
