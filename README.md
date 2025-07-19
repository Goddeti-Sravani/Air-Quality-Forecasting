# 🌫️ Air Quality Prediction Using Ensemble Learning

## 🔍 Overview
This project predicts air quality (Good/Bad) using ensemble learning algorithms. It applies machine learning techniques such as **Random Forest**, **Support Vector Machine (SVM)**, and **Decision Tree** to classify air quality based on environmental attributes like PM2.5, PM10, NO2, CO, O3, etc. The system focuses on accurate and interpretable predictions to help monitor pollution levels and assist in urban planning or public health awareness.

---

## 📂 Dataset
- **Input Features**: PM2.5, PM10, NO2, SO2, CO, O3, Temperature, Humidity, Wind Speed
- **Target Variable**: Air Quality label (Binary - Good / Bad)
- **Source**: Public repositories like Kaggle/UCI Machine Learning Repository

---

## 🛠️ Methodology

1. **Data Preprocessing**
   - Missing value handling
   - Outlier detection using Z-Score and IQR
   - Feature selection and scaling (`StandardScaler`)

2. **Model Training**
   - Algorithms Used:
     - Random Forest
     - SVM (Support Vector Machine)
     - Decision Tree
   - Hyperparameter tuning with GridSearchCV
   - Cross-validation to ensure model stability

3. **Model Evaluation**
   - Metrics Used:
     - Accuracy
     - Precision
     - Recall
     - F1-Score
   - Confusion matrix and visualizations for performance insight

---

## 📊 Results

| Model         | Accuracy | Precision | Recall | F1 Score |
|---------------|----------|-----------|--------|----------|
| Random Forest | 94.5%    | 94.0%     | 95.1%  | 94.5%    |
| SVM           | 92.3%    | 91.8%     | 91.0%  | 91.4%    |
| Decision Tree | 89.2%    | 88.5%     | 89.7%  | 89.1%    |

✅ **Random Forest** performed the best with high accuracy and balanced evaluation metrics.

---
## 🧾 Conclusion
The project successfully builds a region-sensitive, feature-based air quality prediction system. Using ensemble learning techniques, it achieves strong classification results and supports real-world applications in smart city planning and environmental monitoring. The combination of preprocessing, model selection, and evaluation ensures robust performance.

---

## 🚀 Future Scope

- Integrate with real-time air quality sensor APIs
- Develop a user-friendly dashboard or mobile app for live predictions
- Deploy on edge devices like Raspberry Pi or NVIDIA Jetson for real-time use
- Use deep learning models (e.g., LSTM) for time-series prediction
- Expand to multi-class prediction (Good, Moderate, Poor, Hazardous)


