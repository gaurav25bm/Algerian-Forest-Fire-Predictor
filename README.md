# Algerian Forest Fire Predictor

A machine learning web application that predicts the **Forest Fire Weather Index (FWI)** based on meteorological data from the Sidi Bel-abbes and Mascara regions of Algeria.

## 🚀 Live Demo
Check out the live application here: [https://algerian-forest-fire-predictor-8sqh.onrender.com](https://algerian-forest-fire-predictor-8sqh.onrender.com)

## 🛠️ Technologies Used
* **Python 3.14**
* **Flask** (Web Framework)
* **Scikit-Learn** (Machine Learning - Ridge Regression)
* **Pandas & Numpy** (Data Manipulation)
* **Gunicorn** (Production Server)
* **Render** (Deployment & CI/CD)

## 📊 Dataset Information
The dataset includes weather observations like Temperature, Relative Humidity (RH), Wind Speed (Ws), and Rain. The target variable is the **FWI**, which helps in identifying the risk level of forest fires.

## 💻 How to Run Locally
1. Clone the repo: `git clone https://github.com/gaurav25bm/Algerian-Forest-Fire-Predictor.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the app: `python application.py`