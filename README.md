# 🍎 Apple Disease Detection using Deep Learning

## 📌 Project Overview
This project is a deep learning-based system for detecting diseases in apple fruits.  
It uses a pretrained EfficientNetB0 model to classify images into different disease categories.

---

## 🧠 Model Details
- Model: EfficientNetB0 (Transfer Learning)
- Framework: TensorFlow / Keras
- Input Size: 224x224
- Training Strategy:
  - Stage 1: Feature extraction (frozen base model)
  - Stage 2: Fine-tuning (last layers unfrozen)

---

## 📊 Performance
- Training Accuracy: ~85%
- Validation Accuracy: ~87%
- Real-world accuracy: ~90% (approx)

---

## 🗂 Classes
The model classifies apple images into the following categories:
- Anthracnose
- Black Pox
- Black Rot
- Healthy
- Powdery Mildew

---

## ⚙️ Features
- Upload image and get prediction
- High accuracy classification
- Lightweight and efficient model
- Can be integrated into web applications

---

## 🚀 How to Use

1. Load the trained model
2. Upload an apple image
3. Get predicted disease and confidence score

---

## 📥 Model Download

Due to file size limits, the trained model is stored on Google Drive:

[Download Model](https://drive.google.com/file/d/1e0NICj3z4K9j7HiglSH8EQ6IZo8D2ZYX/view?usp=drive_link)

---

## 📁 Files in Repository
- AppleDiseaseDetection.ipynb → Training and prediction code
- README.md → Project documentation

---

## 🔮 Future Improvements
- Web application with login system
- User and admin dashboard
- Database for storing prediction history
- Mobile app integration

---

## 👤 Author
- HEMALATHA SIVAKAI
- Email: sivakavihemalatha@gmail.com
