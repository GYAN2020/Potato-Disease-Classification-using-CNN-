# 🥔 Potato Disease Classification using CNN

A deep learning project that classifies potato leaf images into **Healthy**, **Early Blight**, and **Late Blight** using a Convolutional Neural Network (CNN). The model is trained on the **PlantVillage dataset** with image augmentation and achieves high accuracy.

## 📂 Dataset
[**Kaggle Dataset**](https://www.kaggle.com/datasets/emmarex/plantdisease)

PlantVillage Potato Dataset  
Classes: `Early Blight`, `Late Blight`, `Healthy`

## 🧠 Model Overview
- CNN built with **TensorFlow/Keras**
- Layers: Conv2D, MaxPooling, Dropout, Dense
- Loss: `categorical_crossentropy`
- Optimizer: `adam`

## 🔄 Training
Images preprocessed using `ImageDataGenerator` with rescaling, rotation, zoom, and flipping.

