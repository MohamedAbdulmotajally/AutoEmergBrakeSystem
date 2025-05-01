# 🚗 Auto Emergency Brake System with YOLOv5

This project implements an **automatic emergency braking (AEB)** system using computer vision and object detection. It processes a video input to identify approaching objects, estimate their distance, and trigger braking warnings at various severity levels.

## 🔍 Overview

- 🧠 Powered by **YOLOv5** for real-time object detection.
- 🎯 Calculates object distances using focal length.
- ⚠️ Detects imminent collisions and simulates emergency braking warnings.
- 🎥 Processes video with region-of-interest (ROI) logic and visual alert overlays.

## 📦 Features

- Object detection using YOLOv5 (`yolov5s.pt`)
- Real-time distance estimation
- Visual alerts for:
  - Forward Collision Warning
  - Severe Collision Warning
  - Emergency Stop Alert
- Custom polygonal region of interest (ROI)
- Saves processed video output

## 🛠️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
