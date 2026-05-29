# 🎯 Object Detection and Tracking System

A real-time Object Detection and Tracking System developed using YOLOv8, OpenCV, and Python.  
This project detects and tracks moving objects in video streams while assigning unique tracking IDs to each detected object.

---

# 🚀 Features

- Real-time object detection
- Object tracking with unique IDs
- Bounding box visualization
- Multi-object tracking
- Video processing using OpenCV
- Pre-trained YOLOv8 model
- Output video generation
- Google Colab compatible

---

# 🛠️ Technologies Used

- Python
- OpenCV
- YOLOv8
- Ultralytics
- Google Colab

---

# 📚 Concepts Used

## ✅ Computer Vision
- Image Processing
- Video Frame Processing
- Object Localization

## ✅ Deep Learning
- YOLOv8 Object Detection Model
- Pre-trained Neural Networks

## ✅ Object Tracking
- Persistent Object IDs
- Multi-object Tracking

---

# 📂 Project Workflow

1. Load input video
2. Read video frame-by-frame
3. Detect objects using YOLOv8
4. Track detected objects
5. Draw bounding boxes and tracking IDs
6. Save processed output video

---

# 📸 Output Features

The system can detect and track:

- Person
- Car
- Bus
- Truck
- Motorcycle
- Bicycle

with:
- Bounding Boxes
- Object Labels
- Tracking IDs

Example:

```bash
person #1
car #2
truck #3
````

---

# ▶️ How to Run the Project

## Step 1: Install Required Libraries

```python
!pip install ultralytics
!pip install opencv-python
!pip install filterpy
!pip install lap
```

---

## Step 2: Import Libraries

```python
import cv2
import numpy as np
from ultralytics import YOLO
```

---

## Step 3: Load YOLOv8 Model

```python
model = YOLO("yolov8n.pt")
```

---

## Step 4: Download Sample Video

```python
!wget -O video.mp4 "https://github.com/intel-iot-devkit/sample-videos/raw/master/person-bicycle-car-detection.mp4"
```

---

## Step 5: Run Detection and Tracking

Execute all notebook cells in Google Colab.

---

# 📂 Project Structure

```bash
object-detection-and-tracking/
│
├── TASK_4_Object_Detection_and_Tracking.ipynb
├── output.mp4
└── README.md
```

---

# 🎯 Model Used

## YOLOv8 Nano (yolov8n)

YOLOv8n is a lightweight and fast object detection model optimized for real-time performance.

---

# 📈 Applications

* Smart Surveillance Systems
* Traffic Monitoring
* Autonomous Vehicles
* Security Systems
* Crowd Monitoring
* Smart Cities

---

# 🔮 Future Improvements

* Live webcam support
* DeepSORT integration
* Speed estimation
* Object counting
* Heatmap visualization
* Streamlit web application
* Custom trained models

---

# 💡 Learning Outcomes

This project demonstrates:

* Computer Vision fundamentals
* Real-time object detection
* Video processing
* Deep learning model usage
* Multi-object tracking
* OpenCV integration

---

# 👨‍💻 Author

Muhammad Sufyan

---

# 📄 License

This project is created for educational and internship purposes.

