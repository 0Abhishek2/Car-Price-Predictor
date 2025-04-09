# 🚗 Car Price Predictor App

## 📌 Project Summary

This is a **Machine Learning + Web App** project where a **Linear Regression model** is trained to predict car prices based on inputs like brand, model, mileage, fuel type, etc. The final prediction model is deployed using **Flask**, so users can interact with it through a simple and clean web interface!

---

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| 🐍 **Python** | Core language for data processing and model building |
| 📓 **Jupyter Notebook** | For exploring the data and training the ML model |
| 🐼 **Pandas** | For data wrangling and preprocessing |
| 🔢 **NumPy** | To perform numerical operations |
| 📊 **Matplotlib & Seaborn** | For data visualization and EDA |
| 🤖 **Scikit-learn** | For implementing the Linear Regression ML model |
| 🌐 **Flask** | To build the backend of the web application |
| 🖥️ **HTML/CSS (basic)** | For the frontend of the app (Flask templates) |

---

## 🧠 Machine Learning Flow

1. **Data Cleaning** – Handled missing values, duplicates, and outliers
2. **Feature Encoding** – Converted categorical features to numerical ones
3. **Model Training** – Used `LinearRegression` from scikit-learn
4. **Evaluation** – Tested model with metrics like MAE and R² Score
5. **Model Export** – Saved model using `joblib` for deployment
6. **Deployment** – Loaded model in Flask and created a form for predictions

---

## 🌐 Web App Features

- Input details like year, brand, fuel type, kilometers driven, etc.
- Click **"Predict"** to get an estimated price
- Fast, minimal, and responsive UI

---

## 📂 Folder Structure (Typical)

car_price_predictor/ ├── static/ │ └── style.css ├── templates/ │ └── index.html ├── model/ │ └── car_price_model.pkl ├── app.py ├── notebook.ipynb └── README.md

yaml
Always show details

Copy

---


## ✅ How to Run Locally

```bash
git clone https://github.com/yourusername/car-price-predictor.git
cd car-price-predictor
pip install -r requirements.txt
python app.py
Then open http://127.0.0.1:5000/ in your browser 🚀

📌 Final Thoughts
This project helped me explore:

The full cycle of an ML project 🧠

How to build and deploy a web app using Flask 🌍

Making data-driven predictions with real-world use 🎯 """
