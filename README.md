# 🧠 Parkinson's Disease Detection

An AI-powered machine learning project designed to detect **Parkinson's disease** using biomedical voice measurements.  
This project applies advanced data analysis and classification algorithms to assist in the early detection of Parkinson’s, enabling timely diagnosis and intervention.

---

## 📌 Overview

Parkinson's disease is a progressive neurological disorder that affects movement and speech. Early detection is crucial for improving treatment outcomes.  
In this project, we analyze a dataset containing voice features from healthy individuals and Parkinson's patients, training a machine learning model to classify whether a person may have Parkinson's disease.

---

## ✨ Features

- **Data Preprocessing:** Cleans and scales biomedical voice data.
- **Feature Engineering:** Identifies important predictors using statistical analysis.
- **Model Training:** Uses classification algorithms for disease prediction.
- **Performance Evaluation:** Accuracy, precision, recall, and F1-score metrics.
- **User-Friendly Interface:** (Optional) Streamlit/Flask app for quick predictions.

---

## 🗂 Dataset

- **Source:** UCI Machine Learning Repository – Parkinson's Disease Dataset  
- **Features:** 22 biomedical voice measures including MDVP:Fo(Hz), MDVP:Jitter(%), NHR, etc.  
- **Target Variable:** `status`  
  - `1` → Parkinson's positive  
  - `0` → Healthy control  

---

## 🛠 Tech Stack

- **Languages:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  
- **Model:** SVM (Support Vector Machine) / Random Forest / Logistic Regression  
- **Deployment (optional):** Streamlit / Flask  

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/parkinsons-disease-detection.git
   cd parkinsons-disease-detection
