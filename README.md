# 📦 Research and optimization of delivery processes based on the analysis of logistic data

This project combines theory and practice to explore how **Data Science** and **Machine Learning** can optimize logistics operations. It focuses on improving delivery time and cost predictions using real-world data from **Regal Export LLP**.

---

## 🧠 Abstract

This thesis explores the growing role of analytics in logistics, focusing on how data science techniques — such as **data visualization**, **correlation analysis**, and **predictive modeling** — can improve logistics efficiency. The practical component involves building models that predict delivery **costs** and **times** based on historical data. These models use algorithms like **Linear Regression**, **Random Forest**, and **Neural Networks**, with the best results achieved using Random Forest.

---

## 📊 Features

- Data preprocessing and visualization
- Correlation analysis to identify key delivery factors
- Machine learning models for:
  - Cost prediction
  - Delivery time estimation
- Discount system analysis
- Deployment-ready Streamlit app for visualization and interaction

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn, Plotly
- Geopy, Folium
- Streamlit

---

## 🚀 Getting Started

### Prerequisites

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

---

## 🚛 Delivery Calculator (Streamlit App)

Interactive app for calculating delivery times and costs based on the Random Forest model.

> 📌 Requires `rf_time_model.pkl` and `rf_cost_model.pkl` models in the `/app/` folder

### 🔧 Run the app locally

```bash
streamlit run app/app.py
```
