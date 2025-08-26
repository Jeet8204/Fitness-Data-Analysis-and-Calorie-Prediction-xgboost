## 📌 Project Overview  
This project predicts the **calories burnt** during physical activities based on attributes like gender, age, height, weight, duration, heart rate, and body temperature.  
We use **XGBoost Regressor** with hyperparameter tuning to achieve highly accurate predictions.  

The dataset was sourced from **Kaggle**, containing **1500 records** with **9 features**.  

---

## 🚀 Features  
- Data preprocessing and feature engineering  
- Encoding categorical variables (Gender → Male/Female)  
- Train-test split and model training  
- Hyperparameter tuning with **RandomizedSearchCV**  
- Model evaluation using **MAE, MSE, RMSE, and R² Score**  
- Achieved **R² ≈ 0.999** (almost perfect prediction)  

---

## 📂 Dataset  
The dataset contains:  

- **User_ID** (unique identifier)  
- **Gender** (Male/Female)  
- **Age**  
- **Height (cm)**  
- **Weight (kg)**  
- **Duration (minutes)**  
- **Heart Rate**  
- **Body Temperature (°C)**  
- **Calories (Target Variable)**  

📊 Source: [Kaggle Calories Burnt Dataset](https://www.kaggle.com/)  

---

## ⚙️ Tech Stack  
- **Python 3.8+**  
- **Pandas, NumPy** → Data processing  
- **Matplotlib, Seaborn** → Visualization  
- **Scikit-Learn** → Train-test split, metrics, hyperparameter tuning  
- **XGBoost** → Regression model  

---

## 📈 Results  
- **Test R² Score**: ~0.9994  
- **MAE (Mean Absolute Error)**: ~1.03  
- **MSE (Mean Squared Error)**: ~2.25  
- **RMSE (Root Mean Squared Error)**: ~1.50  

This means the model can predict calorie expenditure with **very high accuracy**.  

---

## 🛠 Installation & Usage  

Clone the repository:  
```bash
git clone https://github.com/your-username/calories-burnt-prediction.git
cd calories-burnt-prediction
