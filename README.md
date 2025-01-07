# Parking Management System Using YOLOv3

## Overview
This project aims to develop an intelligent **Parking Management System** using **YOLOv3 (You Only Look Once)**, an advanced object detection algorithm, for real-time detection and monitoring of parking spaces. The system is designed to improve parking efficiency, reduce search time, and enhance the user experience by guiding drivers to available parking spaces.

## Objectives
1. **Scalability and Adaptability**: Build a scalable solution that can be deployed across various parking facilities such as outdoor parking lots, indoor garages, and multi-level parking structures.
2. **Real-time Detection and Monitoring**: Implement real-time detection and monitoring of parking spaces and vehicles using the YOLOv3 object detection algorithm.
3. **Enhanced User Experience**: Improve the parking experience for drivers by guiding them to available spaces via mobile apps, electronic signage, or other communication channels.

## Methodology

### 1. **Requirement Analysis**
- Analyze the requirements for the parking management system, considering factors such as parking lot size, traffic volume, and types of vehicles.

### 2. **Data Collection and Preparation**
- Collect a diverse dataset of images/videos containing parking lots with varying lighting, vehicle types, and occupancy levels.
- Annotate the dataset to mark the locations of parking spaces and vehicles.

### 3. **Model Training**
- Preprocess the annotated dataset, apply data augmentation techniques (rotation, scaling, flipping).
- Train the YOLOv3 model to optimize detection for parking spaces and vehicles.

### 4. **System Integration**
- Integrate the trained YOLOv3 model into the system for real-time object detection.
- Connect surveillance cameras to capture live video feeds.

### 5. **Real-time Object Detection**
- Implement object detection algorithms using YOLOv3 to identify parking spaces and vehicles in real-time.
- Track vehicles as they enter and exit parking spaces.

### 6. **User Interface Development**
- Design intuitive user interfaces for web dashboards, mobile apps, and electronic signage.
- Display real-time parking availability information for drivers and administrators.

### 7. **Data Analysis and Insights**
- Store and analyze system data for insights into parking occupancy, usage patterns, and historical trends.

### 8. **Testing and Validation**
- Conduct testing to validate system functionality and performance.
- Perform usability testing with end-users for feedback and improvement.

### 9. **Deployment and Maintenance**
- Deploy the system in target parking facilities and ensure proper integration with infrastructure.
- Monitor system performance and address issues through regular maintenance.

### 10. **Training and Support**
- Provide training and support for users and administrators on how to operate and troubleshoot the system.

## Literature Survey

1. **YOLO for Object Detection and Tracking**: Integration of YOLO for vehicle detection and parking efficiency improvement. Reduced parking search time and enhanced the parking experience.
2. **Automatic License Plate Recognition**: Using YOLOv4 for automatic license plate recognition integrated with LINE Bot for parking fee notifications.
3. **ANPR with YOLO and OCR**: Improved OCR accuracy using CNN instead of Tesseract combined with YOLOv4 and contour detection techniques for faster image recognition.
4. **YOLOv8 for Parking Slot Detection**: Real-time parking slot detection using YOLOv8, achieving high accuracy, flexibility, and real-time performance.

## Installation

### Prerequisites
- Python 3.x
- OpenCV
- TensorFlow
- Keras
- PyTorch (for YOLOv3 implementation)
- Other dependencies (can be installed via `requirements.txt`)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/gautamvdwivedi/parking-management-using-computer-vision
   cd parking-management-system-yolov3
