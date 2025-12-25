
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





---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt


## Project Structure
Facial_Expression_Recognition/
train.py – Model training script  
realtime.py – Real-time webcam emotion detection  
model.h5 – Trained CNN model  
requirements.txt – Project dependencies  
README.md – Project documentation  
train/ – Training dataset (image folders)  
test/ – Testing dataset (image folders)

## How to Run the Project
Step 1: Install the required dependencies using the following command:  
pip install -r requirements.txt  

Step 2: Train the CNN model by running:  
python train.py  

Step 3: Run the real-time facial expression recognition system:  
python realtime.py  

Press Q to exit the webcam window.

## Results
The trained CNN model achieves approximately 85% training accuracy and is capable of detecting facial expressions in real time under normal lighting conditions.

## Key Features
Real-time facial expression detection  
CNN-based deep learning model  
Webcam integration using OpenCV  
Modular and clean project structure  

## Future Enhancements
Add emoji overlay for detected emotions  
Improve accuracy using transfer learning models  
Deploy the system as a web application  
Convert the model to TensorFlow Lite for mobile deployment  

## Author
Nirmal Chodavadiya  
Email: nirmalchodavadiya@gmail.com  
GitHub: https://github.com/nirmal-chodavadiya

## Acknowledgements
FER-2013 Dataset provided via Kaggle  
TensorFlow, Keras, and OpenCV documentation
