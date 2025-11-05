# 🫀 HeartWise — Intelligent Cardiovascular Health Management System

## 📋 Overview

**HeartWise** is an AI-powered healthcare application designed for both hospitals and individual users. It predicts cardiovascular and heart disease risk based on vital health parameters and provides personalized insights to promote preventive healthcare. The system leverages machine learning algorithms, trend analytics, and intelligent recommendations to create a comprehensive digital ecosystem for heart wellness.

---

## 🎯 Objectives

* Predict heart and cardiovascular risk using key medical and lifestyle parameters.
* Offer personalized recommendations for diet, exercise, and lifestyle changes.
* Enable users and doctors to monitor trends and visualize progress.
* Support multilingual accessibility and user-friendly dashboards.
* Integrate map-based doctor connectivity for quick consultations.
* Ensure data privacy, accuracy, and healthcare compliance.

---

## 🧠 Key Features

* **AI-Based Risk Prediction:** Uses ML models (Logistic Regression, Random Forest, SVM, XGBoost) to predict heart attack probability.
* **Personalized Insights:** Suggests diets, exercises, and habits based on user data and predicted risk levels.
* **Trend Analysis Dashboard:** Displays progress, statistics, and health history visually.
* **Interactive Health Chatbot:** Provides instant health guidance and query resolution.
* **Doctor & Hospital Locator:** Uses map integration and APIs to connect users with nearby healthcare centers.
* **Data Security:** Encrypts and stores all health data safely for long-term access.

---

## ⚙️ System Architecture

1. **Frontend:** User dashboard and data input interface (HTML/CSS/React).
2. **Backend:** Python-based ML engine with Flask/Django API.
3. **Database:** MySQL / Firebase for secure data storage.
4. **ML Models:** Logistic Regression, Random Forest, SVM, and XGBoost trained on the UCI Heart Dataset.
5. **APIs:** Integration for doctor search and map-based hospital recommendations.

---

## 🧪 Model Performance

| Model               | Accuracy | Precision | Recall   | F1-Score | ROC-AUC  |
| ------------------- | -------- | --------- | -------- | -------- | -------- |
| Logistic Regression | 0.82     | 0.80      | 0.83     | 0.81     | 0.87     |
| Random Forest       | 0.88     | 0.86      | 0.89     | 0.87     | 0.92     |
| SVM                 | 0.85     | 0.83      | 0.86     | 0.84     | 0.89     |
| **XGBoost (Final)** | **0.90** | **0.88**  | **0.91** | **0.89** | **0.94** |

The **XGBoost model** achieved the highest accuracy and was chosen as the final predictive engine.

---

## 💻 Technologies Used

* **Languages:** Python, HTML, CSS, JavaScript
* **Libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn, XGBoost
* **Frameworks:** Flask / Django (for backend), React (for frontend)
* **Database:** MySQL / Firebase
* **APIs:** Google Maps API, Doctor Recommendation API
* **Dataset:** UCI Heart Disease Dataset

---

## 🧩 Functional Workflow

1. User registers and enters medical data (BP, cholesterol, sugar, etc.).
2. Data is processed and analyzed by trained ML models.
3. The system predicts cardiovascular risk (Low / Medium / High).
4. Personalized health recommendations are displayed.
5. Users can visualize progress and connect with nearby doctors.
6. Chatbot assists with daily health queries.

---

## 📱 Future Enhancements

* Integration with wearable health devices for real-time monitoring.
* Mobile application for Android/iOS.
* Deep learning models for more accurate prediction.
* Teleconsultation and e-prescription support.
* Enhanced explainable AI features for medical transparency.

---



