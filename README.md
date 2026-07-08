# 🏠 Real Estate Price Prediction System

> **An Industry-Ready End-to-End Machine Learning Capstone Project**

## 📌 Project Overview

The **Real Estate Price Prediction System** is a production-ready machine learning application that predicts residential property prices based on property characteristics such as area, bedrooms, bathrooms, age, location, and property type.

This project demonstrates the complete machine learning lifecycle, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, deployment, and documentation. It is designed to showcase industry best practices for Data Science and Machine Learning portfolios.

---

# 🎯 Objectives

* Predict residential property prices with high accuracy.
* Build an end-to-end machine learning pipeline.
* Compare multiple regression algorithms.
* Perform feature engineering and preprocessing.
* Deploy the trained model using FastAPI.
* Develop an interactive Streamlit web application.
* Track experiments using MLflow.
* Prepare a production-ready project suitable for GitHub and professional portfolios.

---

# 📂 Dataset

**Dataset:** `house_prices.csv`

### Features

| Feature       | Description                   |
| ------------- | ----------------------------- |
| Property_ID   | Unique Property Identifier    |
| Area          | Property area (sq. ft.)       |
| Bedrooms      | Number of bedrooms            |
| Bathrooms     | Number of bathrooms           |
| Age           | Property age (years)          |
| Location      | Property location             |
| Property_Type | Type of property              |
| Price         | Target variable (House Price) |

---

# 🛠️ Technologies Used

* Python 3.x
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* CatBoost
* TensorFlow / Keras
* FastAPI
* Streamlit
* MLflow
* Docker
* Git & GitHub

---

# 📁 Project Structure

```text
Real-Estate-Price-Prediction/
│
├── data/
│   ├── house_prices.csv
│   └── processed_house_prices.csv
│
├── models/
│   ├── best_model.pkl
│   └── preprocessor.pkl
│
├── notebooks/
│   └── Real_Estate_Price_Prediction.ipynb
│
├── backend/
│   ├── app.py
│   ├── prediction.py
│   └── model_loader.py
│
├── frontend/
│   └── streamlit_app.py
│
├── reports/
│
├── plots/
│
├── logs/
│
├── tests/
│
├── docs/
│
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
└── README.md
```

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Real-Estate-Price-Prediction.git
```

```bash
cd Real-Estate-Price-Prediction
```

---

## 2. Create a Virtual Environment

### Windows

```bash
python -m venv venv
```

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🚀 Running the Project

## Train the Model

```bash
python train.py
```

---

## Start the FastAPI Backend

```bash
uvicorn backend.app:app --reload
```

Open:

```
http://127.0.0.1:8000/docs
```

---

## Run the Streamlit Application

```bash
streamlit run frontend/streamlit_app.py
```

---

# 🤖 Machine Learning Models

The following regression algorithms are implemented and compared:

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor
* CatBoost Regressor
* Neural Network (TensorFlow/Keras)

The best-performing model is selected based on evaluation metrics.

---

# 📊 Evaluation Metrics

The models are evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)
* R² Score

---

# 📈 Exploratory Data Analysis

The project includes:

* Distribution Analysis
* Correlation Analysis
* Scatter Plots
* Histograms
* Box Plots
* Outlier Detection
* Business Insights

---

# 🌐 REST API

### Predict House Price

**POST**

```
/predict
```

### Health Check

**GET**

```
/health
```

### API Documentation

```
/docs
```

---

# 📦 Deployment

The application supports:

* FastAPI Backend
* Streamlit Frontend
* Docker Containerization
* Docker Compose
* MLflow Experiment Tracking

---

# 🧪 Testing

Testing includes:

* Unit Tests
* Integration Tests
* API Tests
* Model Validation
* Performance Testing

---

# 📊 Business Impact

This system helps:

* Real Estate Agencies
* Property Buyers
* Property Sellers
* Financial Institutions
* Real Estate Analysts

### Benefits

* Faster Property Valuation
* Data-Driven Pricing
* Improved Decision-Making
* Reduced Manual Effort
* Scalable Prediction Service

---

# 📚 Future Enhancements

* Larger Real Estate Datasets
* Cloud Deployment (AWS/Azure/GCP)
* Kubernetes Deployment
* Model Drift Detection
* Batch Predictions
* Real-Time Data Integration
* User Authentication
* Interactive Analytics Dashboard

---

# 👨‍💻 Author

**Kailas TS**

**B.Tech – Computer Science and Data Science**

Christ University, Bangalore

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ If you found this project useful

Please consider giving the repository a **⭐ Star** to support the project and make it easier for others to discover.
