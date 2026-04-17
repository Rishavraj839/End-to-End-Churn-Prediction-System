
# End-to-End-Churn-Prediction-System

# 📉 ChurnSense-AI: End-to-End Customer Churn Prediction System

🚀 **Live App:** https://end-to-end-churn-prediction-system-xhdqugxmjyvn7ffomnslhp.streamlit.app/

---

## 🧠 Overview

**ChurnSense-AI** is a complete machine learning system that predicts customer churn in the telecom domain.

Unlike basic ML projects, this application demonstrates:

* Real-world **business problem solving**
* Full **ML lifecycle**
* **Interactive decision-making** via Streamlit

This project is designed to showcase production-level thinking for **AI/ML & GenAI roles**.

---

## ⚡ Key Features

✔️ End-to-End ML Pipeline
✔️ Synthetic + Real Data Handling
✔️ Advanced Feature Engineering
✔️ Class Imbalance Handling using SMOTE
✔️ Model Comparison (Logistic, RF, Gradient Boosting)
✔️ Decision Threshold Tuning (Business Impact Focus)
✔️ Interactive UI with Live Predictions

---

## 🏗️ Architecture

```
Raw Data → Feature Engineering → Preprocessing → 
SMOTE → Model Training → Evaluation → Threshold Tuning → UI Prediction
```

---

## 📊 What Makes This Project Different?

Most churn projects stop at accuracy.

👉 This project goes further:

* Explains **why accuracy is misleading**
* Focuses on **Precision vs Recall trade-off**
* Allows **business-driven threshold tuning**
* Simulates **real-world decision systems**

---

## 🧪 Machine Learning Models Used

* Logistic Regression
* Random Forest
* Gradient Boosting (Best Performing)

---

## 🧬 Feature Engineering Highlights

* Tenure Bucketing (`New`, `Loyal`, etc.)
* Avg Monthly Spend
* Charge Ratio (recency signal)
* Number of Services
* Auto-payment behavior

---

## ⚖️ Handling Imbalanced Data

Used **SMOTE (Synthetic Minority Oversampling Technique)** to:

* Improve recall
* Better capture churn customers

---

## 🎯 Threshold Optimization (Core Highlight)

Instead of default 0.5:

* Adjust threshold dynamically
* Optimize based on **business cost (retention vs loss)**

---

## 🖥️ Streamlit App Features

* 📊 Data Exploration
* 🔧 Feature Engineering Insights
* ⚖️ SMOTE Comparison
* 🎯 Threshold Tuning Dashboard
* 🔮 Real-time Churn Prediction

---

## 🚀 Run Locally

```bash
git clone https://github.com/<your-username>/ChurnSense-AI.git
cd ChurnSense-AI

pip install -r requirements.txt
streamlit run app.py
```

---

## 📂 Project Structure

```
├── app.py
├── data/
│   └── churn.csv (optional)
├── requirements.txt
└── README.md
```

---

## 💡 Learning Outcomes

* Real-world ML pipeline design
* Handling imbalanced datasets
* Feature engineering using domain knowledge
* Business-oriented ML thinking
* Building interactive ML apps

---

## 🔥 Future Improvements

* Deploy using Docker + CI/CD
* Add XGBoost / LightGBM
* Add SHAP explainability
* Connect real-time APIs

---

## 👨‍💻 Author

**Rishav Raj**
AI/ML Engineer | GenAI Developer

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub!
