# 🚀 AI-Powered Customer Churn Prediction API

## 📌 Overview

This project is an end-to-end machine learning pipeline that predicts customer churn using a real-world telecom dataset. It integrates data preprocessing, model training, and deployment through a REST API built with FastAPI.

---

## ⚙️ Tech Stack

* Python
* FastAPI
* Scikit-learn
* Pandas
* NumPy
* Uvicorn

---

## 🧠 Features

* End-to-end ML pipeline (data → model → API)
* Real-time prediction using REST API
* Data preprocessing (cleaning, encoding, scaling)
* Feature alignment for consistent inference
* Lightweight and deployable backend

---

## 📊 Model Details

* Algorithm: Logistic Regression
* Accuracy: ~79%
* Evaluation Metrics:

  * Confusion Matrix
  * Precision, Recall, F1-score

---

## 📂 Project Structure

```
churn-prediction-api/
│
├── app.py
├── train_model.py
├── model.pkl
├── scaler.pkl
├── columns.json
├── requirements.txt
├── sample_input.json
├── README.md
└── notebooks/
    └── churn_model_training.ipynb
```

---

## 🚀 How to Run

### 1. Clone repository

```bash
git clone https://github.com/your-username/churn-prediction-api.git
cd churn-prediction-api
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Train model (optional)

```bash
python train_model.py
```

### 4. Run API

```bash
uvicorn app:app --reload
```

### 5. Open API Docs

```
http://127.0.0.1:8000/docs
```

---

## 🧪 API Usage

### Endpoint: `POST /predict`

#### Example Input

Use `sample_input.json`

#### Example Output

```json
{
  "churn_prediction": 0
}
```

* `0` → Customer likely to stay
* `1` → Customer likely to churn

---

## 💡 Key Learnings

* Building production-ready ML pipelines
* Handling categorical data with one-hot encoding
* Maintaining feature consistency between training and inference
* Deploying ML models using FastAPI

---

## 🚀 Future Improvements

* Improve model performance using XGBoost or Random Forest
* Deploy API on cloud platforms (Render, AWS, GCP)
* Add frontend dashboard (Streamlit/React)
* Implement model monitoring and logging

---

## 👨‍💻 Author

Simran Sarkar
