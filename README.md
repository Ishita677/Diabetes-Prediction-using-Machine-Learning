# Diabetes Prediction using Machine Learning

This project predicts whether a person is diabetic or not using machine learning. It is implemented using **Gradient Boosting Classifier** with hyperparameter tuning for better accuracy. The project was developed and run on **Google Colab**.

## 🚀 Features

* Data preprocessing and standardization
* Model training with hyperparameter tuning (**RandomizedSearchCV**)
* Performance evaluation
* Prediction system for new user input

## 🔧 Tech Stack

* Python
* Google Colab
* Pandas
* Scikit-learn

## 📁 Dataset

* Dataset: `diabete.csv`
* Features include:

  * Pregnancies
  * Glucose
  * BloodPressure
  * SkinThickness
  * Insulin
  * BMI
  * DiabetesPedigreeFunction
  * Age
  * Outcome (0 = Non-Diabetic, 1 = Diabetic)

## 📜 How to Run

1. Open the notebook in **Google Colab**
2. Upload `diabete.csv` to the Colab session
3. Run the cells step by step to preprocess data, train the model, evaluate, and make predictions

## ✅ Example Prediction

* Input: `(5, 166, 72, 19, 175, 25.8, 0.587, 51)`
* Output: `The person is diabetic.` or `The person is not diabetic.`
