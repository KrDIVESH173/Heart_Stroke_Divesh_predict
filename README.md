# ❤️ Heart Stroke Prediction App

A machine learning powered web application built with **Streamlit** that predicts the risk of heart disease based on patient health parameters.

## 🚀 Live Demo
Try the app here: [Heart Stroke Predictor](https://heart-stroke-divesh-predict.streamlit.app)

---

## 📊 Features
- User-friendly form to input patient details:
  - Age, Sex, Chest Pain Type
  - Resting Blood Pressure, Cholesterol
  - Fasting Blood Sugar, Resting ECG
  - Max Heart Rate, Exercise Induced Angina
  - Oldpeak (ST Depression), ST Slope
- Real-time prediction using a trained **KNN model**
- Clear output: **Low Risk** or **High Risk**
- Deployed seamlessly on **Streamlit Cloud**

---

## 🛠️ Tech Stack
- **Python**
- **Streamlit** for web interface
- **Scikit-learn** for machine learning
- **Pandas & NumPy** for data handling
- **Joblib** for model persistence

---

## 📂 Project Structure
- `app.py` → Main Streamlit app
- `heart.csv` → Dataset
- `KNN_heart.pkl` → Trained KNN model
- `scaler.pkl` → Scaler for normalization
- `columns.pkl` → Column metadata
- `requirements.txt` → Dependencies

---

## ⚡ Run Locally
Clone the repo and install dependencies:

```bash
git clone https://github.com/KrDIVESH173/Heart_Stroke_Divesh_predict.git
cd Heart_Stroke_Divesh_predict
pip install -r requirements.txt
streamlit run app.py
