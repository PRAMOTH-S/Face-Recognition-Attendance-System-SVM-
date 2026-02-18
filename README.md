# 🎯 Face Recognition Attendance System (SVM)

This project is a **Face Recognition based Attendance System** built using **Python + OpenCV + Machine Learning (SVM)**.  
It detects faces from a webcam, extracts **128-D face embeddings**, trains an **SVM classifier**, and recognizes people in real-time to mark attendance.

---

## ✨ Features
- 📷 Real-time face recognition using webcam  
- 🧠 **SVM Algorithm** for classification  
- 🔍 128-D face embeddings for accurate identification  
- 🧾 Stores student details (Name + RollNo)  
- 📌 Marks attendance automatically in `attendance.csv`  
- 💾 Saves trained model for reuse  

---

## ⚡ Workflow
- Dataset Creation (Name + RollNo)
- Face Detection + Pre-processing
- Extract 128D Face Embeddings
- Train Model using **SVM**
- Real-time Recognition + Attendance Logging

---

## 🛠️ Installation

```bash
pip install opencv-python numpy face-recognition
pip install sklearn
