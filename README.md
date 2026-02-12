# Crowd-Flow-Analyzer

Real-time crowd flow analysis for CCTV feeds using SSD (Single Shot Detector).

## Features
- Real-time person detection on CCTV streams
- Tracking via centroid tracker
- Alerting (email / live notifications)
- Configurable via `utils/config.json`

## Tech Stack
Python, OpenCV, SSD (Caffe), NumPy

## Performance
- SSD: **80% detection accuracy @ 59 FPS**
- YOLO (baseline): **65% @ 45 FPS**

## Setup
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
