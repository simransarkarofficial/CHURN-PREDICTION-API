# 🚀 AI-Powered Customer Churn Prediction API

## 📌 Overview

This project is an end-to-end machine learning pipeline that predicts customer churn using a real-world telecom dataset. The system processes input data, performs feature engineering, and provides real-time predictions via a REST API.

---

## ⚙️ Tech Stack

* Python
* FastAPI
* Scikit-learn
* Pandas
* Uvicorn

---

## 🧠 Features

* Real-time churn prediction API
* Data preprocessing pipeline (encoding, scaling)
* Model deployment using FastAPI
* JSON-based input/output
* Feature alignment for consistent inference

---

## 📊 Model Details

* Algorithm: Logistic Regression
* Accuracy: ~79%
* Evaluation: Confusion Matrix, Precision, Recall

---

## 🚀 How to Run

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Run API

```bash
uvicorn app:app --reload
```

### 3. Open API Docs

```
http://127.0.0.1:8000/docs
```

---

## 🧪 Sample Input

Use `sample_input.json` for testing the `/predict` endpoint.

---

## 📌 API Endpoint

### POST `/predict`

Returns churn prediction:

* `1` → Customer likely to churn
* `0` → Customer likely to stay

---

## 💡 Future Improvements

* Use XGBoost for better performance
* Deploy on cloud (Render/AWS)
* Add frontend dashboard

---

## 👨‍💻 Author

Your Name
