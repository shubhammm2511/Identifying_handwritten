# Handwritten Digit Recognition Web App

This project is a machine learning web application that identifies handwritten digits (0–9) using a Logistic Regression model built with PyTorch and deployed using Streamlit Cloud.

🔗 **Live Demo:**  
https://identifyinghandwritten-ajtsgu4t9appep5fwhnhns.streamlit.app/

---

## 📌 Project Overview

Handwritten digit recognition is a classic machine learning problem commonly solved using the MNIST dataset.  
In this project, a Logistic Regression classifier is trained using PyTorch and integrated into an interactive Streamlit web application that allows users to:

- Draw a digit using a canvas
- Upload an image of a handwritten digit
- Get real-time predictions with confidence

---

## 🚀 Features

- Interactive digit drawing canvas
- Image upload support (PNG, JPG)
- Real-time digit prediction
- Confidence score for predictions
- Clean and user-friendly UI
- Deployed on Streamlit Cloud

---

## 🧠 Model Details

- **Algorithm:** Logistic Regression  
- **Framework:** PyTorch  
- **Dataset:** MNIST Handwritten Digits  
- **Input Size:** 28 × 28 pixels  
- **Output Classes:** Digits 0–9  
- **Accuracy:** ~82% on test data  

The trained model is saved using `state_dict()` and loaded during runtime in the Streamlit app.

---

## 🛠️ Tech Stack

- Python  
- PyTorch  
- Streamlit  
- NumPy  
- Pillow  
- streamlit-drawable-canvas  

---

## 📁 Project Structure

