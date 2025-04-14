# AI Soccer Fatigue Tracker Project

## Introduction
The goal of this project is to detect and track players and referees to track their fatigue on a percentage base using YOLO, one of the best AI object detection models available. We will also train the model to improve its performance. We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and distance covered to estimate their fatigue. This project covers various concepts and addresses real-world problems, making it suitable for both beginners and experienced machine learning engineers.

<img width="1470" alt="Screenshot 2025-04-13 at 9 58 42 PM" src="https://github.com/user-attachments/assets/b5dc327b-c29e-46b1-bda7-7699dcf30b8b" />

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed, distance and fatigue calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
