# IBM-Cloud-Project-on-Power-System-Fault-Detection-
A machine learning-based fault detection system for electrical power grids using voltage and current phasor data. Deployed with IBM Cloud Watson for real-time classification and prediction of faults like line breakage, overheating, and transformer failure.


# ⚡ Power System Fault Detection

This project presents a machine learning solution for detecting and classifying faults in power systems using voltage and current phasor data. The model is trained on labeled fault data and deployed via IBM Watson Machine Learning for real-time prediction.

---

## 🧩 Problem Statement

Power grids are susceptible to various faults such as:
- Line-to-ground
- Line-to-line
- Three-phase faults

Manual detection is inefficient and slow. The goal is to automate fault detection using real-time measurements to ensure grid reliability and safety.

---

## ✅ Proposed Solution

We use a supervised learning approach with Random Forest to:
- Train a model on labeled fault data from Kaggle
- Deploy the model on IBM Cloud
- Predict fault types using real-time electrical input data

---

## 🛠️ System Requirements

- IBM Cloud Lite account
- Python 3.8+
- Jupyter Notebook
- Libraries:
  - `pandas`, `numpy`, `matplotlib`
  - `scikit-learn`
  - `ibm_watson_machine_learning`

---

## 🧪 Algorithm & Deployment

- **Algorithm:** Random Forest Classifier
- **Features:** Voltage/Current Magnitudes & Phase Angles
- **Training:**
  - 80/20 train-test split
  - Normalization and hyperparameter tuning with `GridSearchCV`
- **Deployment:**
  - IBM Watson Machine Learning
  - REST API endpoint for inference

---

## 🚀 Results

| Fault Type          | Confidence |
|---------------------|------------|
| Transformer Failure | 35%        |
| Line Breakage       | 39%        |
| Overheating         | 37%        |

---

## 🔮 Future Scope

- Integrate SCADA for real-time data input
- Use deep learning models (LSTM/CNN) for better accuracy
- Add predictive maintenance features
- Deploy on edge devices for faster response

---

## 📚 References

- [Kaggle Dataset](https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset)
- IBM Cloud Documentation: [cloud.ibm.com](https://cloud.ibm.com)
- IEEE Research Papers on Power Fault Detection
- 
