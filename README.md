# 🏥 Insurance Premium Predictor

A machine learning web application that estimates annual medical insurance 
premiums based on personal and lifestyle details. Built with Python, 
Streamlit, and a Decision Tree Regression model.

## 🔗 Live App
👉 **[Click here to try the app](https://insurance-premium-pasindu.streamlit.app)**

---

## 📌 Overview
Insurance premiums vary widely based on individual characteristics. 
This app uses a trained machine learning model to instantly estimate 
what a person's annual medical insurance cost might be — based on 
key demographic and lifestyle factors.

---

## ✨ Features
- 🔮 Instant annual premium prediction
- 📅 Monthly premium breakdown
- ⚠️ Risk level indicator (Low / Moderate / High)
- 📋 Full profile summary after prediction
- 💡 Personalised health tips based on risk level

---

## 🧠 How It Works
The model was trained on a US medical insurance dataset (1,337 records).
Key factors that influence the premium:

| Factor | Impact |
|---|---|
| Smoking Status | Strongest predictor |
| BMI | High impact |
| Age | Moderate impact |
| Number of Children | Low impact |
| Region & Sex | Minimal impact |

---

## 🚀 How to Use
1. Open the **[Live App](https://insurance-premium-pasindu.streamlit.app)**
2. Enter your details:
   - Age, Sex, BMI
   - Smoking status
   - Number of children
   - Residential region
3. Click **Predict My Premium**
4. View your estimated annual and monthly premium instantly

---

## 🛠️ Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core language |
| Streamlit | Web app framework |
| Scikit-learn | Machine learning |
| Decision Tree Regression | Prediction model |
| GridSearchCV | Hyperparameter tuning |
| Pandas & NumPy | Data processing |
| GitHub + Streamlit Cloud | Deployment |

---

## 📊 Model Performance
| Metric | Score |
|---|---|
| Test R² | 0.8992 |
| MAE (Test set) | ~$4,303 |
| RMSE (Test set) | ~$2,503 |
| CV R² (5-fold) | 0.8469 |

---

## 👨‍💻 Author
**Pasindu Jayasundara**  
IS 4007 — Statistics in Practice II
