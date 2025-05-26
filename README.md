# SurveilNet: AI-Powered Traffic Density Analysis Using YOLOv8

## 📌 Project Overview
**SurveilNet** is an AI-driven traffic density analysis system designed to process images of **Indian urban roads** and detect vehicles and pedestrians in dense traffic scenarios. By leveraging **YOLOv8 (You Only Look Once) object detection**, this project extracts key insights from traffic images, facilitating **real-time monitoring, congestion analysis, and urban mobility planning**.

---

## 🎯 Project Aim
The goal of this project is to:
- ✅ **Detect vehicles & pedestrians** in traffic-heavy images.
- ✅ **Analyze traffic density** by counting detected objects.
- ✅ **Improve urban mobility solutions** using AI-powered insights.
- ✅ **Prepare high-quality annotated datasets** for further AI research.

This project serves as a **foundational step toward smart traffic management**, helping city planners, transportation authorities, and AI researchers **optimize road networks** using data-driven methodologies.

---

## 🛠️ Project Methodology
### 1️⃣ Dataset Preparation
- 📂 Uploaded **ZIP file containing dense traffic images** in `.jpg` format.
- 📦 Extracted dataset using Python's `zipfile` module.
- 📁 Organized images for seamless AI processing.

### 2️⃣ Object Detection Using YOLOv8
- 🚀 Used the **Ultralytics YOLOv8** model, a state-of-the-art deep learning framework for object detection.
- 🎯 YOLOv8 detected **vehicles, pedestrians, traffic signs, and road infrastructure** in images.
- 🖼️ **Annotated images** with bounding boxes highlighting detected objects.

### 3️⃣ Traffic Density Analysis
- 📊 Counted detected vehicles and pedestrians to measure **congestion levels**.
- 📈 Plotted **density trends over multiple images**, providing visual insights into road traffic patterns.

### 4️⃣ Model Enhancements & Optimization
- ⚡ Fine-tuned detection accuracy by optimizing YOLOv8 parameters.
- 📍 Eliminated detection errors using **threshold adjustments**.
- 🛣️ Expanded dataset for more robust AI learning.

---

## ✨ Key Achievements
✔ **Successfully processed traffic images** to detect vehicles & pedestrians.  
✔ **Achieved real-time traffic density analysis**, quantifying congestion levels.  
✔ **Enhanced annotation accuracy** by fine-tuning YOLOv8's detection capabilities.  
✔ **Created a scalable AI framework** that can integrate with **smart city initiatives** for better traffic management.  

---

## 🔜 Future Improvements
🚥 **Vehicle Classification** – Categorizing objects (cars, buses, bikes, pedestrians, etc.).  
📍 **Traffic Flow Prediction** – Using AI models to forecast congestion trends.  
💻 **Dashboard Visualization** – Developing an interactive UI to display real-time traffic data.  
📡 **Live Camera Integration** – Extending analysis beyond static images to **real-time CCTV footage**.  

---

## 🏗️ How to Run the Project
### 1️⃣ Install Dependencies
Run the following command to install required libraries:
```bash
pip install ultralytics opencv-python numpy zipfile36 matplotlib google-colab
