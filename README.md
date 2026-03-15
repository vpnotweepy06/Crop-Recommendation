# Crop-Recommendation - ML based crop recommendation system using Flask

# 🌱 Crop Recommendation System

A Machine Learning based web application that recommends the most suitable crop to grow based on soil nutrients and environmental conditions.

This project uses a trained ML model to analyze input parameters such as Nitrogen, Phosphorus, Potassium, temperature, humidity, pH value, and rainfall to predict the best crop for cultivation.

---
📌 Project Overview

Choosing the right crop based on soil and climate conditions is crucial for improving agricultural productivity.
This system helps farmers and users by predicting the best crop using input parameters such as soil nutrients and weather conditions.

The project demonstrates the complete Machine Learning lifecycle, including:

Data preprocessing

Model training and evaluation

Model persistence

Web application deployment

Version control using GitHub

---
## 🚀 Features

* Predicts the most suitable crop using machine learning
* Simple and user-friendly web interface
* Built with a Flask web application
* Uses trained ML models for prediction
* Real-time crop recommendation

---

## 🧠 Machine Learning Model

The model was trained using a crop recommendation dataset containing soil and environmental parameters.

**Input Features**

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature
* Humidity
* pH value
* Rainfall

The trained model predicts crops such as:

* Rice
* Maize
* Chickpea
* Kidney Beans
* Pigeon Peas
* Moth Beans
* Mung Bean
* Black Gram
* Lentil
* Pomegranate
* Banana
* Mango
* Grapes
* Watermelon
* Muskmelon
* Apple
* Orange
* Papaya
* Coconut
* Cotton
* Jute
* Coffee

---

## 🛠 Technologies Used

* Python
* Flask
* NumPy
* Pandas
* Scikit-learn
* HTML / CSS

---

## 📂 Project Structure

```
crop-recommendation-ml
│
├── app.py
├── requirements.txt
├── README.md
│
├── models
│   ├── final_model.pkl
│   ├── scaler.pkl
│   └── label_encoder.pkl
│
├── notebook
│   └── Crop_Recommendation.ipynb
│
├── templates
│   └── index.html
```

---

## ⚙️ Installation

Clone the repository from GitHub:

```
git clone https://github.com/vpnotweepy06/crop-recommendation.git
```

Move into the project folder:

```
cd crop-recommendation
```

Install required dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Flask server:

```
python app.py
```

Open your browser and go to:

```
http://127.0.0.1:5000
```

Enter the soil and environmental values to get a crop recommendation.

---

## 📊 Model Workflow

1. Dataset preprocessing and analysis using Jupyter Notebook
2. Feature scaling using StandardScaler
3. Model training using Random Forest Classifier
4. Model and scaler saved using pickle
5. Flask application loads the trained model
6. User inputs are processed and prediction is displayed on the web page

---

## 📌 Future Improvements

* Deploy the application online
* Add prediction confidence score
* Improve UI design
* Add visualization of soil parameters
* Build a mobile-friendly interface

---

## 👩‍💻 Author

Vishnupriya Rajan

GitHub:
https://github.com/vpnotweepy06
