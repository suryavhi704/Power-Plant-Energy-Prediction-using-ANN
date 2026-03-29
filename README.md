# ⚡ Power Plant Energy Prediction using ANN (PyTorch)

## 🚀 Project Overview

This project focuses on predicting **power plant energy output** using an **Artificial Neural Network (ANN)** built with **PyTorch**. The model learns complex relationships between environmental variables and energy production, achieving an impressive **93% accuracy**.

---

## 📊 Problem Statement

Predict the **Produced Energy (MW)** of a power plant based on:

* 🌡 Temperature
* 🌀 Vacuum
* 🔵 Pressure
* 💧 Humidity

---

## 🛠 Tech Stack

* Python 🐍
* PyTorch 🔥
* NumPy & Pandas
* Scikit-learn (Preprocessing)
* Gradio (Deployment UI)

---

## 🔄 Project Workflow

### 1️⃣ Data Import & Preprocessing

* Loaded Power Plant dataset
* Handled missing values and cleaned data
* Applied feature scaling for model efficiency

### 2️⃣ Tensor Conversion

* Converted dataset into **PyTorch tensors**
* Enabled compatibility with deep learning pipeline

### 3️⃣ TensorDataset & DataLoader

* Wrapped tensors into `TensorDataset`
* Used `DataLoader` for:

  * Batch processing
  * Efficient training
  * Better memory handling

### 4️⃣ ANN Model Development

* Built a fully connected neural network:

  * Input Layer: 4 features
  * Hidden Layers: Dense + ReLU
  * Output Layer: 1 (Regression output)

### 5️⃣ Training & Evaluation

* Loss Function: MSELoss
* Optimizer: Adam
* Achieved **~93% accuracy**
* Evaluated using test dataset

### 6️⃣ Model Deployment

* Integrated trained model with **Gradio UI**
* Interactive sliders for input
* Real-time prediction display

---

## 🎯 Key Features

* ⚡ High-performance ANN model
* 📦 Efficient data pipeline using DataLoader
* 🎛 Interactive user interface with Gradio
* 🎨 Professional black-red themed UI
* 🚀 Deployment-ready architecture

---

## 📸 Demo Preview

![Image](https://github.com/suryavhi704/Power-Plant-Energy-Prediction-using-ANN/blob/main/Screenshot%202026-03-26%20123741.png?raw=true)

---


## 💡 Future Enhancements

* 📊 Model Explainability (SHAP)
* 📈 Prediction Visualization Dashboard
* 🌐 Cloud Deployment (Hugging Face / AWS)

---

## 👨‍💻 Author

**Suryavhi Das**

---

## ⭐ If you like this project, give it a star!
