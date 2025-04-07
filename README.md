# Efficient Detection of DDoS Attacks Using Machine Learning

This project aims to efficiently detect Distributed Denial of Service (DDoS) attacks using various machine learning algorithms. The system is built to analyze network traffic data and classify it as normal or malicious based on a rich set of features.

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Methodology](#methodology)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)

---

## ✅ Overview

The goal of this project is to improve the accuracy of DDoS detection using machine learning techniques. We compare and evaluate the performance of four models and aim to reduce false positives while maintaining high detection rates.

---

## 📊 Dataset

- The dataset contains **73 features**, including:
  - Source/Destination Address
  - Packet ID, Type, Size
  - Flow Duration
  - Total Fwd/Backward Packets
  - Packet Length Mean
  - Flow Bytes/s, Packets/s
  - Label (Normal / Attack)

---

## 🔍 Features

- Data Preprocessing & Cleaning
- Feature Selection & Dimensionality Reduction
- Model Building with:
  - Logistic Regression
  - Random Forest
  - Neural Networks
  - Multi-Layer Perceptron (MLPClassifier)
- Model Evaluation & Comparison

---

## ⚙️ Methodology

1. **Data Preprocessing**: Cleaning, handling missing values, and scaling features using `StandardScaler`.
2. **Exploratory Data Analysis**: Visualizing trends and patterns using Matplotlib and Seaborn.
3. **Model Training**: Applying different ML models to detect DDoS attacks.
4. **Evaluation**: Using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.
5. **Comparison**: Analyzing model performance to choose the best detection method.

---

## 🤖 Models Used

- **Logistic Regression** (Improved accuracy from 80% → 95%)
- **Random Forest Classifier**
- **Neural Network (NN)**
- **MLPClassifier** (Multi-layer Perceptron)

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve and AUC Score

---

## 🏆 Results

| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Random Forest      | 0.9995   | 1.0000    | 0.9990 | 0.9995   |
| Logistic Regression| 0.9447   | 0.9102    | 0.9931 | 0.9499   |
| Neural Network     | 0.9824   | 0.9922    | 0.9743 | 0.9832   |


## 💻 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ddos-detection-ml.git
   cd ddos-detection-ml
