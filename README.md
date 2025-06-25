# AI-Based-Casting-Defect-Detection

This repository contains the code, models, and deployment setup used for my Master's thesis:  
**"AI-Based Casting Defect Detection Using Deep Learning and Cloud Deployment."**

---

## 📌 Overview  
The objective of this work is to develop an intelligent quality control system to detect casting defects in submersible pump impellers using deep learning models.

This study compares the performance of the following architectures for **binary classification** of casting defects:

- **MobileNetV2**  
- **ResNet50**  
- **Xception**  
- **EfficientNet**

Comprehensive evaluation was conducted using metrics such as **accuracy**, **precision**, **recall**, and **F1-score** to identify the optimal model for industrial deployment.

---

## ☁️ Cloud Deployment  
The best-performing model was deployed using a **Streamlit-based web interface**, containerized using **Docker**, and made scalable for cloud-based inference to ensure real-time industrial applicability.

---

## 🛠️ Features

- Clean, preprocessed grayscale dataset of 7,348 impeller images  
- Modular deep learning training pipeline  
- Performance visualization and metrics comparison  
- Streamlit web interface for live defect prediction  
- Cloud-ready containerized architecture (Docker)

---

## 📂 Dataset

The dataset used in this study is publicly available here:

🔗 [Casting Product Image Dataset (Kaggle)](https://www.kaggle.com/datasets/ravirajsinh45/real-life-industrial-dataset-of-casting-product)

Please download the dataset and place it in the `data/` directory.

---

## 📦 Repository Structure

