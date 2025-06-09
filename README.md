
# 🧑‍⚕️ Multiple Disease Prediction System using Machine Learning

This project is a **Streamlit-based web application** that predicts the likelihood of three major diseases:

- **Diabetes**
- **Heart Disease**
- **Parkinson’s Disease**

It uses trained machine learning models saved in `.sav` format and provides predictions based on user inputs.

---

## 📌 Features

- 🚀 Built with **Streamlit** for a simple and interactive UI
- 💡 Predicts disease risk from medical parameters
- 🧠 Uses pre-trained ML models (`.sav` files)
- 🎯 Accurate predictions tested on standard datasets
- 📁 Easy to run locally with Python

---

## 📂 Folder Structure

project-root/
│
├── MultipleDiseasePrediction.py # Streamlit web app
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── saved_models/ # Folder with trained ML models
├── diabetes_model.sav
├── heart_disease_model.sav
└── parkinsons_model.sav

2. Install Requirements
It's recommended to use a virtual environment:

pip install -r requirements.txt

3. Run the Streamlit App
The app will open in your browser at http://localhost:8501/.

📦 Required Libraries
Make sure your requirements.txt includes:
streamlit
scikit-learn
pandas
numpy
streamlit-option-menu


📊 Input Parameters Used
🔹 Diabetes:
Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age

🔹 Heart Disease:
Age, Sex, Chest pain type, Cholesterol, Resting BP, etc.

🔹 Parkinson’s:
MDVP:Fo(Hz), Jitter(%), Shimmer, HNR, PPE, etc.



