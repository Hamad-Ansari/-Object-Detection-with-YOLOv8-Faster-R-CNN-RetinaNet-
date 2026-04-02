<div align="center">

# 🚀 Object Detection with YOLOv8, Faster R-CNN & RetinaNet  
### 🔍 Multi-Architecture Detection Pipeline | Deep Learning Project  

👨‍💻 **Developed by Hammad Zahid**  
🎓 AI • Data Science • Computer Vision Enthusiast  

</div>

---

## 🧠 Project Overview

This project implements **state-of-the-art object detection** using three powerful deep learning architectures:

- ⚡ **YOLOv8** — Fast, real-time object detection using Ultralytics  
- 🎯 **Faster R-CNN** — High-accuracy detection via Detectron2  
- 🧩 **RetinaNet** — Balanced performance using focal loss (Detectron2)  

The goal is to **compare performance, training behavior, and detection quality** across different architectures on a custom dataset.

---

## 📦 Dataset

- 📁 Source: **Roboflow**
- 📌 Formats Used:
  - YOLOv8 format
  - COCO format (for Detectron2)
- 🧪 Used for:
  - Training
  - Validation
  - Cross-model evaluation

---

## ⚙️ Tech Stack

| Category            | Tools & Libraries |
|--------------------|------------------|
| 🤖 Models           | YOLOv8, Faster R-CNN, RetinaNet |
| 🧠 Frameworks       | PyTorch, Detectron2 |
| 📊 Visualization    | Matplotlib, Plotly |
| 📷 Computer Vision  | OpenCV (cv2), MediaPipe |
| 🗂️ Data Handling    | Pandas, NumPy |
| 📈 Evaluation       | scikit-learn |
| ☁️ Platform         | Google Colab (GPU) |

---

## 📊 Results & Evaluation

### 📌 YOLOv8 Performance
- 🎯 **mAP@50**: `0.426`
- 📉 **mAP@50-95**: `0.299`
- ⚡ Trained for **5 epochs**

### 📌 Detectron2 Models
- 📉 **Faster R-CNN & RetinaNet**
  - Show consistent **loss reduction**
  - Strong learning convergence

### 📈 Evaluation Metrics
- ✅ Confusion Matrix  
- ✅ Precision-Recall Curve  
- ✅ F1 Score Curve  

---

## 🧪 Model Comparison Insight

| Model         | Speed ⚡ | Accuracy 🎯 | Use Case |
|--------------|--------|-----------|---------|
| YOLOv8       | High   | Medium    | Real-time detection |
| Faster R-CNN | Medium | High      | Precision-critical tasks |
| RetinaNet    | Medium | Balanced  | Class imbalance handling |

---

## ▶️ How to Run

💻 This project is optimized for **Google Colab with GPU**

### 🔹 Step 1: YOLOv8 Pipeline
```bash
Open: Yolov8.ipynb
```
Detectron2 Pipeline
```
Open: RetinaNet_and_Faster_R_CNN.ipynb
```
Install Dependencies
```
pip install ultralytics detectron2 roboflow
```
