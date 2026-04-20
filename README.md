# 🌱 Crop vs Weed Detection using YOLOv11 (Mobile Application)

## 📌 Project Overview
This project focuses on detecting crops and weeds in real agricultural fields using a deep learning model (YOLOv11) and deploying it as a mobile application. The system helps farmers identify weeds efficiently and supports precision agriculture.

---

## 📊 Dataset Collection
- Dataset was **personally collected** from methi crop fields at the University.
- Videos were recorded daily under **real field conditions**.
- Captured at different:
  - Times of the day (lighting variation)
  - Growth stages of plants
  - Background environments

### 🔄 Data Processing
- Videos → Converted into **image frames**
- Generated around **23,000+ images**
- Split into:
  - Training set
  - Validation set
  - Test set

---

## 🏷️ Annotation
- Tool used: **LabelImg**
- Classes:
  - Crop 🌿
  - Weed 🌱
- Each image manually annotated with bounding boxes

---

## 🤖 Model Details
- Model: **YOLOv11**
- Accuracy: **~99%**
- Trained on custom dataset for real-world performance

---

## 📱 Mobile Application
- Framework: **Flutter (Android)**
- Model converted to: **TensorFlow Lite (TFLite)**

### 🚀 Features
- 📷 Capture image using camera
- 🖼️ Upload image from gallery
- 🎯 Real-time detection with:
  - Bounding boxes
  - Confidence scores
- 📍 GPS tracking (Latitude & Longitude)
- 📄 Export results to CSV file
- 🤖 Supports future robot navigation

---

## 📦 APK Download
Download the app here:
https://github.com/Kanchana-86/Crop_weed_detection/releases/download/v1.0/app-release.apk

---

## 🛠️ Installation Steps
1. Download the APK file from this repository
2. Transfer to your Android device
3. Enable **"Install from Unknown Sources"**
4. Install and open the app

---

## 📷 Sample Output
https://github.com/Kanchana-86/Crop_weed_detection/blob/main/App%20UI.jpg
---

## 📈 Applications
- Smart Farming 🌾
- Precision Agriculture
- Weed Control Automation
- Agricultural Robotics

---

## 🔮 Future Improvements
- Real-time video detection
- Integration with IoT devices
- Autonomous robot deployment
- Cloud-based analytics
