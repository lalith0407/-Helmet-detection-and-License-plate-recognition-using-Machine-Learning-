# Helmet Detection and License Plate Recognition System

## Overview
This project implements a **YOLO-based object detection system** to detect helmet usage and recognize license plates in real-time, aiding traffic rule enforcement and public safety. By leveraging domain-specific datasets and advanced machine learning techniques, the system achieves an **85% detection accuracy** for helmets, ensuring compliance and scalability.

## Key Features
- **YOLO-Based Object Detection**:
  - Utilized **YOLOv5** for high-precision helmet detection and license plate recognition.
  - Fine-tuned the model with custom annotations to enhance detection accuracy on traffic-specific datasets.

- **Real-Time Processing**:
  - Enabled real-time video analysis for live monitoring and enforcement scenarios.

- **Data Engineering**:
  - Designed a scalable data pipeline for preprocessing, cleaning, and augmenting datasets to improve model robustness.

- **Performance Optimization**:
  - Evaluated model performance with precision, recall, and F1-score metrics to ensure reliability in diverse traffic conditions.

## Technologies Used
- **Machine Learning Frameworks**:
  - **YOLOv5**: For object detection and fine-tuning.
  - **PyTorch**: Backend framework for model development and training.
- **Data Engineering Tools**:
  - **Pandas** and **NumPy**: For data manipulation and preprocessing.
- **Visualization**:
  - Integrated tools for real-time visual feedback and detection monitoring.

## Workflow
1. **Data Collection and Annotation**:
   - Collected real-world traffic video data for helmet detection and license plate recognition.
   - Annotated datasets with bounding boxes for helmets and license plates using labeling tools.

2. **Model Training**:
   - Preprocessed and augmented datasets with techniques like flipping, scaling, and noise addition.
   - Fine-tuned **YOLOv5** on the annotated datasets to optimize detection accuracy.

3. **Validation and Testing**:
   - Evaluated model performance on independent datasets using **precision (85%)**, recall, and F1-score.
   - Tested scalability with real-time video feeds to ensure responsiveness.

4. **Deployment**:
   - Integrated the detection model into a live monitoring system for traffic enforcement applications.

## Performance Metrics
- **Helmet Detection Accuracy**: 85%
- **Precision**: High precision validated on independent datasets.
- **Real-Time Capability**: Optimized for low-latency video analysis.
