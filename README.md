
# 🎭 Facial_Expression_Recognition
**Real-time Facial Expression Recognition using CNN**

---

## 📌 Project Overview
This project implements a **real-time facial expression recognition system** using
**Convolutional Neural Networks (CNN)** and **Computer Vision** techniques.
The system detects human faces from live webcam input and classifies facial
expressions into predefined emotion categories.

The trained deep learning model is integrated with **OpenCV** to perform
real-time emotion prediction.

---

## 🧠 Technologies Used
- Python  
- TensorFlow  
- Keras  
- OpenCV  
- NumPy  
- Matplotlib  
- Pandas  

---

## 📂 Dataset
- **FER-2013 (Facial Expression Recognition Dataset)**
- 48×48 grayscale facial images
- 7 emotion classes:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Sad
  - Surprise
  - Neutral

🔗 Dataset link:  
https://www.kaggle.com/datasets/msambare/fer2013

---

## ⚙️ Project Structure
Facial_Expression_Recognition/
│
├── train.py # Model training script
├── realtime.py # Real-time webcam emotion detection
├── model.h5 # Trained CNN model
├── requirements.txt # Project dependencies
├── README.md # Project documentation
│
├── train/ # Training dataset (image folders)
│ ├── angry/
│ ├── disgust/
│ ├── fear/
│ ├── happy/
│ ├── sad/
│ ├── surprise/
│ └── neutral/
│
└── test/ # Testing dataset (image folders)
├── angry/
├── disgust/
├── fear/
├── happy/
├── sad/
├── surprise/
└── neutral/




---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt

---

### 2️⃣ Train the CNN Model
```bash
python train.py

---

### 3️⃣ Run Real-Time Facial Expression Recognition
```bash
python realtime.py

---


Press Q to exit the webcam window.


