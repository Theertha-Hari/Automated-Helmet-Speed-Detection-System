# Helmet Speed Detection using YOLO

This project is a computer vision–based traffic monitoring system that detects **helmet violations** and **estimates vehicle speed** from video footage using YOLO and object tracking.

It can be used as a smart traffic violation detection system for road safety monitoring.

---

## Features

- Helmet / no-helmet detection using **YOLO**
- Motorcycle and rider detection  
- Vehicle speed estimation using frame-to-frame tracking  
- Real-time video processing with OpenCV  
- Violation highlighting in output video  

---

## Tech Stack

- **Python**  
- **YOLO**  
- **OpenCV**  
- **PaddleOCR**  
- **SQLite**  
- **Base64**  
---

## How It Works

1. Video is processed frame by frame  
2. YOLO detects motorcycles, riders, and helmets  
3. Vehicles are tracked across frames  
4. Speed is estimated based on movement  
5. Helmet and over-speed violations are flagged  

---

## How to Run

```bash
git clone https://github.com/your-username/Helmet-speed-detection.git
cd Helmet-speed-detection
pip install -r requirements.txt
python main.py
```

---

## Applications

Traffic surveillance, road safety monitoring, and automated violation detection.
