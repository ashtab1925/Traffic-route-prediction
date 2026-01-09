# Traffic Prediction Using Machine Learning 🚦

## 📌 Project Overview
**Traffic-Prediction-using-Machine-Learning** is a research-based practice project focused on predicting traffic congestion levels using machine learning techniques.  
The project compares the performance of two models:
- **Random Forest Classifier**
- **Support Vector Regression (SVR)**

The objective is to analyze traffic patterns based on temporal, environmental, and zonal features and accurately predict traffic density.

---

## 🧠 Problem Statement
Traffic congestion is influenced by several factors such as day of the week, weather conditions, and temperature.  
This project aims to:
- Predict traffic congestion levels
- Compare classification and regression-based ML approaches
- Evaluate model performance using accuracy and error metrics

---

## 📊 Dataset Description

The dataset consists of traffic data collected across different zones and days with the following attributes:

### 🔹 Features
- **Date**  
  The date when the data was recorded (Format: `DD/MM/YYYY`)

- **Day**  
  The weekday corresponding to the date (Monday to Sunday)

- **Coded Day**  
  Numerical representation of weekdays for easier model training:
  - Monday → 1  
  - Tuesday → 2  
  - Wednesday → 3  
  - Thursday → 4  
  - Friday → 5  
  - Saturday → 6  
  - Sunday → 7  

- **Zone**  
  Zone number where traffic data was collected.  
  This also includes encoded weather conditions such as:
  - Humidity
  - Visibility
  - Mist
  - Precipitation

- **Temperature**  
  Temperature recorded for the given zone on a particular day

### 🎯 Target Variable
- **Traffic**  
  Traffic density level encoded on a 5-point scale:
  - **1** → Less than 5 cars  
  - **2** → 5 to 15 cars  
  - **3** → 15 to 30 cars  
  - **4** → 30 to 50 cars  
  - **5** → More than 50 cars  

---

## ⚙️ Machine Learning Models Used

### 1️⃣ Random Forest Classifier
An ensemble learning method that builds multiple decision trees and merges their outputs for better accuracy and stability.

### 2️⃣ Support Vector Regression (SVR)
A regression-based approach that finds an optimal hyperplane to predict continuous traffic levels with minimal error.

---

## 📈 Performance Comparison

| Model                     | Error (%) | Accuracy (%) |
|--------------------------|-----------|--------------|
| Random Forest            | 13.42     | 86.58        |
| Support Vector Regression| 12.16     | 87.84        |

✔️ **SVR achieved the highest accuracy and lowest error rate**, making it the better-performing model for this dataset.

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

---

---

## 🔍 Key Learnings
- Feature encoding plays a critical role in traffic prediction
- Environmental factors significantly influence traffic patterns
- SVR can outperform classification models for traffic density prediction

---

## 📚 Reference
This project is inspired by and adapted from the following repository:  
🔗 https://github.com/Nupurgopali/Traffic-Prediction-using-SVR-and-RFR

---

## 👤 Author
**Abubakar Siddqique**  
📧 Email: ashtab1925@gmail.com  
🔗 GitHub: https://github.com/ashtab1925  

---

⭐ *If you find this project helpful, feel free to star the repository!*

