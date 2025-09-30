# qml-rain-prediction

# 🌧️ Quantum Rain Prediction with PennyLane

This project demonstrates how **Quantum Machine Learning (QML)** can be applied to a real-world classification problem: predicting rainfall based on weather data.  
We use **PennyLane** to build and train a **Variational Quantum Circuit (VQC)**, bridging quantum computing concepts with classical machine learning workflows.

---

## 📖 Background

Traditional machine learning methods have been widely used in weather prediction tasks.  
This project explores whether **quantum-enhanced models** can capture nonlinear relationships in small-scale datasets by encoding classical weather data into quantum states.

The model classifies whether **rain occurred** (`1`) or **did not occur** (`0`) based on features:
- **TMAX** — Maximum temperature  
- **TMIN** — Minimum temperature  
- **PRCP** — Precipitation  

---

## 🎯 Objectives

- Load and preprocess a weather dataset (`4129666.csv`)  
- Encode features into a **quantum circuit** using data re-uploading  
- Train a **variational quantum classifier** with gradient descent  
- Evaluate accuracy on unseen test data  
- Visualize predictions with scatter plots  

---

## 📂 Project Structure

