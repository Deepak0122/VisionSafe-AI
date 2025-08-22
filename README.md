# VisionSafe-AI
AI-powered traffic and road safety system using YOLO and ESP32-CAM for crash, helmet, drowsiness, and traffic violation detection
# 🚦 VisionSafe AI – AI-Powered Traffic & Road Safety System  

## 📌 Overview  
VisionSafe AI is an **end-to-end AI-powered traffic and road safety solution** designed to save lives, enforce traffic rules, and improve urban mobility.  
It integrates **YOLO-based computer vision** with **ESP32-CAM live feeds** to provide real-time monitoring, alerts, and analytics.  

## 🛠️ Features (Modules)  
- 🚗 **Crash Detection** – Detects accidents and sends instant alerts to emergency contacts.  
- 🪖 **Helmet Violation Detection** – Identifies riders without helmets.  
- 😴 **Driver Drowsiness Detection** – Monitors driver fatigue through eye/yawn detection.  
- 🚦 **Smart Traffic Control** – Adaptive traffic light system based on vehicle density.  
- 🔍 **Number Plate Recognition (ANPR)** – YOLO + OCR for automatic number plate recognition.  

## ⚡ Tech Stack  
- **Hardware:** ESP32-CAM, CCTV Integration  
- **AI Models:** YOLO (Object Detection), OCR (for ANPR)  
- **Languages:** Python, OpenCV, PyTorch  
- **Dashboard:** Streamlit/Flask (for live monitoring & analytics)  
- **Alerts:** GSM/IoT Integration for emergency notifications  

## 🚀 How It Works  
1. **ESP32-CAM / CCTV** streams live feed.  
2. **YOLO Models** process frames in real time.  
3. **Violations/Events** (helmet, crash, drowsiness, etc.) are detected.  
4. **Dashboard & Alerts** – Violations are logged, emergency alerts sent, and traffic signals updated dynamically.  

## 📊 Impact  
- Saves lives with **faster crash & drowsiness detection**  
- Reduces congestion with **adaptive traffic control**  
- Automates enforcement of **traffic rule violations**  
- Scalable for **city-wide deployment** at low cost  

## 📽️ Demo  
👉 [Demo Video Link](#) *(upload to Google Drive / YouTube and update here)*  

## 📂 Project Structure  
```
├── data/                # Datasets for training
├── models/              # YOLO models and weights
├── dashboard/           # Streamlit/Flask dashboard
├── esp32/               # ESP32-CAM integration code
├── notebooks/           # Training & testing notebooks
└── README.md            # Project documentation
```

## 👨‍💻 Team  
**Team Name:** VisionSafe AI  
- Deepak Chand (Lead – AI/ML)  
- [Add other teammates if any]  

## 📬 Contact  
📧 Email: mathadeepakchand@gmail.com  
📱 Phone: +91 9133618422  

---
✨ *“Let’s make roads safer with AI.”* ✨
