# 🐔 Poultry Health Monitoring System (Deep Learning & Data Science)

**Technologies:** Python, TensorFlow, PyTorch, YOLOv8, OpenCV, Pandas, NumPy, Flask

---

## 🧠 Overview
AI-powered system for detecting poultry diseases through posture-based image analysis. Uses YOLOv8 for object detection and CNN for disease classification (e.g., coccidiosis, fowlpox). Designed to improve early disease diagnosis and farm health monitoring.

---

## 🎯 Objectives
- Detect and classify chickens as Normal or Abnormal
- Identify specific diseases: Coccidiosis, Newcastle, Fowlpox, Leg Disease
- Enable real-time monitoring with frame counting
- Compare object detection and classification accuracy across two approaches

---

## 🔍 Approach 1: Roboflow Labeling + YOLOv8 + CNN

### 🔧 Data Collection & Labeling
- Collected 500K+ chicken images
- Labeled with Roboflow: 'Normal' vs 'Abnormal'

### 📦 Object Detection (YOLOv8)
- Trained on Google Colab
- Detected chickens in images/videos with 98% accuracy

### 🧠 Disease Classification (CNN)
- Classified diseases with 92% accuracy
- Final system accuracy: 96%

### 🎥 Frame Counting
- Counted Normal/Abnormal chickens across frames for real-time monitoring

---

## 🔁 Approach 2: YOLOv8 + Basic CNN Classification

### 📸 Frame Extraction
- Extracted multiple frames from labeled data for better training

### 🧠 CNN Classification
- Classified chickens as 'Normal' or 'Abnormal' (no disease-level classification)

### 🧪 Testing
- Achieved 99% classification accuracy on frames
- Some issues observed on video frame sequence

---

## 📊 Final Results

| Task                        | Accuracy |
|-----------------------------|----------|
| Object Detection (YOLOv8)   | 98%      |
| CNN Disease Classification  | 92%      |
| Overall Model Accuracy      | 96%–99%  |

---

## 🧪 Output
- 🐔 Normal vs Abnormal classification
- 🐔 Disease-specific detection: Fowlpox, Leg Disease, etc.
- 📊 Frame-based health analytics

---

## ✅ Conclusion
The system demonstrates effective use of deep learning in poultry farming. Combining YOLOv8 and CNN enabled both detailed disease analysis and simple classification, offering valuable insights for proactive farm management.
