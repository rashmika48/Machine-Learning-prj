# Intelligent Pattern Recognition Using Equilibrium Optimizer with Deep Learning Model for Android Malware Detection

## 🧠 Project Overview

This project presents an **Android malware detection system** using **Machine Learning (ML)** enhanced by the **Equilibrium Optimizer (EO)** for optimized feature selection. It aims to improve cybersecurity by identifying malicious applications using intelligent pattern recognition techniques.

Built using:
- **Python (3.9)** with **Flask (2.2)** for backend
- **HTML/CSS/JavaScript + Bootstrap 5 + Chart.js** for responsive frontend
- **ML models**: Extra Tree Classifier and Logistic Regression
- Dataset: [TUNADROMD](https://tunadromd.org)

---

## 📊 Key Features

- **High Accuracy**: Extra Tree Classifier (97.23%), Logistic Regression (93.67%)
- **Smart Feature Selection**: 23 best features chosen from 242 using Mutual Information Scoring
- **Real-Time Detection**: Fast scan (<50ms) on mid-range Android devices
- **Lightweight Deployment**: Uses <3% battery/hour and supports Android 10+
- **Explainable AI**: Includes performance visualization and interpretability features

---

## 📁 Project Structure

```bash
├── app.py                  # Flask backend
├── templates/              # HTML templates
│   ├── index.html
│   ├── login.html
│   ├── upload.html
│   ├── preview.html
│   ├── prediction.html
│   └── performance.html
├── static/                 # Static files (CSS/JS)
├── logic_malware.pkl       # Trained Logistic Regression model
├── ExtraTree_malware.pkl   # Trained Extra Tree Classifier model
└── README.md
