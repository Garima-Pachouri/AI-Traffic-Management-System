# AI-Based Traffic Management System

## Overview
This project focuses on improving traffic signal timing using vehicle detection. It uses basic computer vision techniques to estimate traffic density and simulate adaptive signal control.

## Tech Stack
- Python
- OpenCV
- YOLO (concept)
- Arduino (concept)

## Features
- Detects vehicles from video frames
- Estimates traffic density
- Displays vehicle count on screen
- Simulates adaptive signal timing logic

## How It Works
- Video input is captured using OpenCV
- Frames are processed to detect vehicles
- Vehicle count is calculated
- Based on count, signal timing logic can be adjusted

## My Contribution
I worked on understanding the detection logic and implementing a basic version of the system using Python and OpenCV.

## Project Structure
AI-Traffic-Management-System/ 
 ├── main.py
 ├── README.md

## How to Run
1. Install dependencies:
   pip install opencv-python
2. Run the file:
   python main.py

## Future Improvements
- Integrate real YOLO model
- Connect with Arduino for real signals
- Improve detection accuracy
