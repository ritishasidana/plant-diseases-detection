 # 🌱 Plant Disease Prediction System for Sustainable Agriculture

An end-to-end **Deep Learning–based Plant Disease Detection System** that identifies plant diseases from leaf images using a **CNN model trained on a large agricultural dataset**.  
The system is deployed using **Streamlit** for real-time image prediction.

---

## 📌 Project Overview

Plant diseases significantly reduce crop yield and farmer income. This project aims to assist farmers and agricultural experts by providing an **automated plant disease recognition system** using computer vision and deep learning.

The model classifies plant leaf images into **39 different disease and healthy categories** with high accuracy.

---

## 🚀 Features

- 🌿 Detects **plant diseases from leaf images**
- 🧠 Uses a **Convolutional Neural Network (CNN)**
- 📊 Trained on a **large augmented dataset**
- 🖼️ Supports **real-time image upload**
- ⚡ Fast and interactive **Streamlit web app**
- ✅ Covers **multiple crops** (Apple, Tomato, Potato, Grape, Corn, etc.)

---

## 🧠 Dataset

- **Name:** New Plant Diseases Dataset (Augmented)
- **Source:** Kaggle
- **Total Classes:** 39
- **Type:** RGB Leaf Images

🔗 **Dataset URL:**  
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

---

## 🧠 Pretrained Model

- **Model Type:** CNN (Keras / TensorFlow)
- **Input Size:** 224 × 224 × 3
- **Classes:** 39

🔗 **Pretrained Model URL:**  
https://drive.google.com/drive/folders/1AGJj0MlimxURn2P_48mKh03mn7tyizB5?usp=drive_link

> ⚠️ Place the downloaded model file as:  
> `plant_disease_cnn_model.keras` in the project root directory.

---

## 🏗️ Tech Stack

- **Programming Language:** Python
- **Deep Learning:** TensorFlow / Keras
- **Image Processing:** OpenCV
- **Web App:** Streamlit
- **Data Handling:** NumPy
- **Visualization:** PIL

---

## 🧪 Model Details

- Input Shape: `224 × 224 × 3`
- Architecture: Custom CNN
- Output: 39 plant disease classes
- Loss Function: Categorical Crossentropy
- Optimizer: Adam

---

## 🖥️ Web Application (Streamlit)

The Streamlit app allows users to:
1. Upload a plant leaf image
2. View the uploaded image
3. Predict the disease using the trained CNN model

### Sample Prediction Output
```text
Model is predicting that it is a Tomato : Late blight
