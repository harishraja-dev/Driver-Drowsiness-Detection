# Driver-Drowsiness-Detection
Real-time driver drowsiness detection system using MediaPipe, OpenCV, and facial landmark analysis.

A real-time driver drowsiness detection system developed using Computer Vision, MediaPipe, and OpenCV to improve road safety by detecting eye closure and yawning patterns.

The system analyses facial landmarks from live or recorded video input and classifies the driver as DROWSY or NOT DROWSY based on temporal behavioral analysis.

## Project Overview

The project uses facial landmark detection to monitor:

- Eye closure
- Blink patterns
- Yawning behavior
- Fatigue indicators

The system generates alerts when prolonged eye closure or continuous yawning is detected.

## Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy

## Features

- Real-time face detection
- Facial landmark extraction
- Eye Characteristic Ratio (ECR)
- Mouth Aspect Ratio (MAR)
- Temporal drowsiness analysis
- Automatic alert generation

## Working Principle

1. Video frames are extracted from input video
2. Face detection is performed using MediaPipe
3. Facial landmarks are identified
4. ECR and MAR values are computed
5. Temporal analysis is applied across multiple frames
6. Driver state is classified as:
   - DROWSY
   - NOT DROWSY

## Detection Logic

- ECR threshold ≈ 0.15
- MAR threshold ≈ 0.6
- Eye closure detected for 45 frames
- Yawning detected for 60 frames

## Dataset Used

YawDD Dataset (Kaggle)

The dataset contains:
- Drowsy driving videos
- Yawning patterns
- Eye closure behavior
- Different lighting conditions

## Applications

- Driver Safety Systems
- Smart Vehicles
- Automotive AI
- Fatigue Monitoring
- Road Safety Systems

## Files Included

- Python Source Code
- Presentation Slides
- Demonstration Videos
- Workflow Diagrams

## Future Improvements

- Real-time webcam deployment
- Audio alarm system
- Deep learning based classification
- Mobile integration
- Night-time optimization

## Author

Harish Raja  
ECE Undergraduate, VNIT Nagpur
