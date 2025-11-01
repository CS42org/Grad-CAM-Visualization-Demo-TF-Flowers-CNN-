# 🌸 Grad-CAM Visualization Demo (TF-Flowers CNN)

### 🔍 Overview
This project shows how to use **Grad-CAM (Gradient-weighted Class Activation Mapping)** to visualize the focus area of a Convolutional Neural Network (CNN) trained on the **TensorFlow Flowers** dataset.

Grad-CAM helps explain *where* the model is looking when making predictions — a key part of **Explainable AI (XAI)**.

---

### 📦 Features
- Loads and preprocesses the **TF-Flowers** dataset (5 flower classes)
- Builds a **simple CNN** for image classification
- Computes **Grad-CAM heatmaps** for model predictions
- Visualizes both original and highlighted images side-by-side

---

### 🧰 Requirements
Install dependencies using:
```bash
pip install -r requirements.txt

### 🧰 Output 
#Sample of the dataset
<img width="640" height="184" alt="Sample images" src="https://github.com/user-attachments/assets/62e669f0-cae1-4902-b322-a5103afa42cd" />

#Grad-CAM output
<img width="783" height="2157" alt="Output" src="https://github.com/user-attachments/assets/f527fea2-21a3-4335-8bc1-d3c50c71b9ed" />
