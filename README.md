# Hand Sign Recognition Project using MediaPipe and OpenCV

This project is an implementation of a hand sign recognition system using [MediaPipe](https://google.github.io/mediapipe/) and [OpenCV](https://opencv.org/). The goal of this project is to detect and recognize different hand signs from a live video feed.

## Prerequisites

Before you begin, you will need the following: 
- [MediaPipe](https://google.github.io/mediapipe/) 
- [OpenCV 4+](https://opencv.org/releases/) 


## Usage 
1. First you need to detect number of hand landmarks and create CSV file using Landmarks
2. Feed the model with a live video feed for detection and recognition of different hand signs
3. Create Machine Learning model to classify signs based on values of landmarks
4. run real time video to detect these signs
