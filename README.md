# Real-Time-Traffic-Density-Estimation
Real-time traffic density estimation and signal control using YOLOv11, OpenCV, and Flask

## 📌 Project Overview
This project is a real-time intelligent traffic management system using Machine Learning and Computer Vision. It detects vehicles from CCTV/video input and dynamically adjusts traffic signals based on congestion levels.

## 🚀 Features
- 🚗 Real-time vehicle detection using YOLOv11
- 📊 Traffic density estimation (Low / Medium / High)
- 🚦 Dynamic traffic signal control
- 🚑 Ambulance priority system
- 📈 Live dashboard using Flask
- 🔐 User authentication

## 🧠 Technologies Used
- Python
- OpenCV
- YOLOv11
- Flask
- NumPy
- SQLite

## ⚙️ How It Works
1. Video input is taken from CCTV or uploaded file
2. Frames are extracted using OpenCV
3. YOLOv11 detects vehicles in each frame
4. Vehicle count is used to estimate traffic density
5. Signal timing is adjusted dynamically

## 📊 Results
- Accuracy: 95–97%
- Speed: 20–30 FPS
- Works effectively in dense traffic conditions

## 🎥 Demo Video
👉 https://drive.google.com/file/d/1b9vFyJUW-GXnjXJZzBlZA5zIaitw8EEU/view?usp=sharing

## 📦 Model Download
👉 Install yolov11 model from ultralytics

## 📄 Research Paper
This project is supported by a conference paper included in the repository.

## 🚀 How to Run

bash
pip install -r requirements.txt
python app.py

📌 Future Improvements
Multi-camera support
Traffic prediction using AI
Smart city integration
