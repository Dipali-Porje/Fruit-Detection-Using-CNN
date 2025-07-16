# 🍎 Fruit Detection System using CNN with Tkinter GUI

This project is a deep learning-based **fruit classifier** that identifies different types of fruits from images using a **Convolutional Neural Network (CNN)** and provides a clean **desktop interface built using Tkinter**.

---

## 🍌 Classes Detected

The model is trained to classify the following fruits:
- 🍎 Apple
- 🥭 Mango
- 🍊 Orange
- 🍇 Grapes
- 🍍 Pineapple
- 🍉 Watermelon
- 🍌 Banana
- 🍑 Pomegranate  

---

## 🧠 Model Info

- Architecture: **CNN (Convolutional Neural Network)**
- Input Size: e.g., **150 x 150** or **224 x 224**
- Output: Fruit class label + prediction confidence
- Framework: **TensorFlow/Keras**

---

## 🖥️ GUI Features (Tkinter)

- 📤 Upload image of any fruit
- 🔍 Classify using the trained CNN model
- 📋 Display prediction result on-screen
- 🔁 Reset and upload new images easily

---

## 🗂️ Project Structure

fruit_detection/
├── fruit_model.h5 # Trained CNN model
├── fruit_prediction_model.ipynb 
├── prediction.ipynb

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Dipali-Porje/Fruit-Detection-Using-CNN.git
cd Fruit-Detection-Using-CNN

### 2️⃣ Install Dependencies
pip install -r requirements.txt

### 🌟 Future Enhancements

Add real-time fruit classification from webcam
Show top-3 predictions with confidence bars
Enhance UI with TTK themes or custom styling
