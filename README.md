[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![GitHub Repo Size](https://img.shields.io/github/repo-size/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System)
![GitHub last commit](https://img.shields.io/github/last-commit/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System)
![GitHub language count](https://img.shields.io/github/languages/count/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System)
![GitHub stars](https://img.shields.io/github/stars/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System?style=social)
![GitHub forks](https://img.shields.io/github/forks/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System?style=social)

# 📈 Stock Market Prediction Web App (Real-Time + ML)

A **Stock Market Analysis and Prediction Web App** built using **FastAPI** and **React**. The platform fetches **real-time stock data**, performs **7-day price forecasting** using **ARIMA, LSTM, and Linear Regression**, and uses **real financial news sentiment analysis** to recommend BUY/SELL/HOLD actions. Admins can manage users and trigger emails. The system supports **NASDAQ and NSE** stocks.

---

## 📋 Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Built With](#built-with)
- [Installation](#installation)
- [Contributors](#contributors)
- [License](#license)

---

## 🚀 Features

### 👤 User Features
- Register and Login with JWT
- Check real-time stock prices (NASDAQ + NSE)
- View interactive trend charts
- Predict next 7-day prices using 3 ML models (ARIMA, LSTM, Linear Regression)
- Analyze sentiment from financial news headlines
- Get AI-generated investment recommendations
- Currency converter with live exchange rates
- Profile management
- Download stock tickers list
- Fully responsive dashboard

### 🛠 Admin Features
- All user capabilities
- View and manage all users (CRUD)
- Manually trigger notification emails

---


## 🖼️ Screenshots

### 🏠 Home Page
<img src="https://raw.githubusercontent.com/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System/main/frontend/src/assets/Home.png" alt="Home Page" width="100%"/>

### 🧾 About Page
<img src="https://raw.githubusercontent.com/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System/main/frontend/src/assets/About.png" alt="About Page" width="100%"/>

### 💱 Currency Converter
<img src="https://raw.githubusercontent.com/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System/main/frontend/src/assets/CurrencyConverter.png" alt="Currency Converter" width="100%"/>

### 🔐 Login Page
<img src="https://raw.githubusercontent.com/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System/main/frontend/src/assets/Login.png" alt="Login Page" width="100%"/>

### 📝 Register Page
<img src="https://raw.githubusercontent.com/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System/main/frontend/src/assets/Register.png" alt="Register Page" width="100%"/>

### 📝 Dashboard Page
<img src="https://raw.githubusercontent.com/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System/main/frontend/src/assets/Dashboard.png" alt="Register Page" width="100%"/>

### 📝 StockDetails Page
<img src="https://raw.githubusercontent.com/Aishkhansudo/Stock-Market-Analysis-and-Future-Prediction-System/main/frontend/src/assets/StockDetails.png" alt="Register Page" width="100%"/>
---

## 🧰 Built With

![Python](https://img.shields.io/badge/Python-3.10-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?logo=fastapi)
![React](https://img.shields.io/badge/React-20232A?logo=react)
![SQLite](https://img.shields.io/badge/SQLite-07405E?logo=sqlite)
![YFinance](https://img.shields.io/badge/yfinance-yellow)
![NewsAPI](https://img.shields.io/badge/NewsAPI-orange)
![Keras](https://img.shields.io/badge/Keras-FF0000?logo=keras)
![Pandas](https://img.shields.io/badge/pandas-150458?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-9999FF?logo=matplotlib)

---

## ⚙️ Installation

### 🖥 Backend (FastAPI)
```bash
cd backend
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

pip install -r requirements.txt
uvicorn main:app --reload
```

### 🌐 Frontend (React)
```bash
cd frontend
npm install
npm start
```

---

## 🤝 Contributors

- [@Aishkhansudo](https://github.com/Aishkhansudo)
- Nasreen Fatima
---

## 📜 License

This project is licensed under the [MIT License].

---

> ⚠️ **Disclaimer**: Stock predictions are based on machine learning models and real-time news sentiment analysis. This application does not provide financial advice. Always consult a financial expert before making investment decisions.
