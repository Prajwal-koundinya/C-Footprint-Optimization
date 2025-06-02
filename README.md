# C-Footprint-Optimization 
Carbon Footprint Optimizer for Supply Chain Logistics, smart deep learning-powered tool to predict carbon emissions in supply chains based on emission factors and margin data. 

Try out the application which is live 
# 🌱 Carbon Footprint Optimization in Supply Chain Logistics 🚛

A machine learning-powered web application that helps **optimize delivery routes and supply chain decisions** based on **carbon emissions**. This project predicts the **CO₂ equivalent per USD** spent using emission factor data and provides businesses a way to move toward **eco-friendly, sustainable logistics**.

### 🔗 [Carbon Footprint Optimization (Live App)](https://visionary-croissant-257d82.netlify.app/)

---

## 📌 Overview

Traditional logistics systems focus on **cost** and **time**, often ignoring environmental impact. This tool aims to change that by using **data-driven predictions** to estimate carbon emissions associated with different segments of the supply chain.

By entering key emission factor details, users can view estimated emissions and make better decisions for sustainability.

---

## 🚀 Features

- ✅ Predict carbon emissions per dollar spent using a trained ML model
- ✅ Interactive UI built with **HTML + Flask**
- ✅ Clean evaluation metrics: **MAE, RMSE, % error**
- ✅ Live deployment (via Netlify)
- ✅ Supports green decision-making in logistics and supply chain

---

## 🧠 Tech Stack

| Layer        | Technology           |
|--------------|----------------------|
| **Backend**  | Python, Flask        |
| **ML Model** | Scikit-learn, RandomForestRegressor |
| **Frontend** | HTML, CSS (basic)    |
| **Deployment** | Netlify (frontend), Flask (local backend) |

---

## 📊 Machine Learning Approach

- **Model**: Random Forest Regressor
- **Inputs**:  
  - Supply Chain Emission Factors (without margins)  
  - Margins of Emission Factors  
- **Target**:  
  - Total Supply Chain Emission Factors (with margins)
- **Metrics**:
  - MAE: ~0.04
  - RMSE: ~0.51
  - Avg % Error: ~1.23%

---

## 🤝 **Acknowledgments**
Special thanks to the medical and AI communities for their valuable datasets and research.  
Inspirational guidance from **Dr. Victor Ikechukwu**. Explore their work: [Dr. Victor Ikechukwu](https://github.com/Victor-Ikechukwu). 


## 📜 License
This project is licensed under the **MIT License**.

---
🔥 *If you like this project, don't forget to ⭐ it on GitHub!*
