# Early Stampede Risk Detection Using Crowd Density–Motion Fusion

## Overview

This project is a crowd safety system that predicts potential stampede risks by combining **crowd density estimation** and **crowd movement analysis**. Instead of focusing solely on crowd counting, the system identifies dangerous crowd behavior and provides early warnings before a critical situation develops.

## Key Features

* **Crowd Density Estimation** using CSRNet
* **Movement Analysis** using Optical Flow
* **Density–Motion Fusion Risk Score**
* **Offline Deployment** on edge devices
* **Visual Alerts and Risk Monitoring**

## System Workflow

1. Capture video from CCTV/Webcam.
2. Estimate crowd density using CSRNet.
3. Analyze crowd motion using Optical Flow.
4. Compute a risk score from density and motion patterns.
5. Classify risk as:

   *  Low
   *  Medium
   *  High
6. Trigger alerts when abnormal crowd behavior is detected.

## Technologies Used

* Python
* PyTorch
* OpenCV
* CSRNet
* YOLOv8
* Optical Flow (Lucas–Kanade / Farnebäck)

## Datasets

* ShanghaiTech Crowd Dataset
* JHU-CROWD Dataset


## Project Goal

To provide an affordable and practical early-warning system that helps authorities identify crowd instability and prevent stampedes in public gatherings.

## Core Idea

**"The system does not aim to count people precisely; it aims to detect early crowd instability by fusing crowd density and abnormal motion patterns to prevent stampedes."**
