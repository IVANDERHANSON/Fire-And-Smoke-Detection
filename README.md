# 🔥 Fire & Smoke Detection using YOLOv8 + ResNet18

Sistem deteksi api dan asap berbasis **deep learning** yang menggabungkan **object detection** dan **image classification** untuk meningkatkan akurasi dan keandalan deteksi kebakaran.

---

## <img width="50" height="30" alt="image" src="https://github.com/user-attachments/assets/cf9a67cd-bc62-4302-b897-55c891234539" /> Colab Version

https://colab.research.google.com/drive/1ST3gpvqD-jz2Xq4V1dXCFjsTwICvf7Ly?usp=sharing

---

## 📌 Overview

Project ini menggunakan pendekatan **hybrid model**:
- **YOLOv8** → mendeteksi lokasi api & asap (bounding box)
- **ResNet18** → memverifikasi apakah gambar termasuk *fire*, *smoke*, atau *neutral*

Pendekatan ini membantu:
- Mengurangi **false positive**
- Meningkatkan **akurasi sistem**
- Mendukung **real-time detection**

---

## 🧠 Architecture
Input Image

├── YOLOv8 → Fire/Smoke Detection (Bounding Box)

└── ResNet18 → fire / smoke / Neutral Classification

- YOLOv8: deteksi objek (fire & smoke)
- ResNet18: klasifikasi global (verifikasi)

---

## 📂 Dataset

Dataset yang digunakan:

- Fire & Smoke Detection Dataset  
  https://www.kaggle.com/datasets/roscoekerby/firesmoke-detection-yolo-v9/data  

- Fire, Smoke, and Neutral Dataset  
  https://www.kaggle.com/datasets/slirq123/fire-smoke-and-neutral/data  

---

## ⚙️ Features

- 🔥 Fire & Smoke Object Detection (YOLOv8)
- 🧠 Fire/Smoke/Neutral Classification (ResNet18)
- 📊 TensorBoard Logging
- 📈 Training Visualization (Loss, Accuracy)
- 💾 Model Saving
- ⚡ Real-time inference ready

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Ultralytics YOLOv8
- OpenCV
- TensorBoard
- NumPy

---
