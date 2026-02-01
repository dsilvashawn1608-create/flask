🔍 Fake Social Media Account Detector

A simple machine learning project that uses Linear Regression to detect fake social media accounts based on a predefined dataset stored in the backend.
The application runs on FastAPI with a basic HTML & CSS frontend.

✨ Description

This project demonstrates the basic workflow of an ML application, including:

Training a simple model using a defined dataset

Loading the trained model in the backend

Accepting user input from a web interface

Returning predictions through a FastAPI endpoint

The goal of this project is learning and demonstration, not production-level accuracy.

🛠️ Technologies Used

Python

NumPy

Scikit-learn

Joblib

FastAPI

HTML & CSS

🧠 Model Details

Model: Linear Regression

Dataset: Predefined dataset inside the backend

Training/Test Split: 80% / 20%

Purpose: Learn ML integration with a web backend

⚠️ Linear Regression is used for simplicity and understanding.
This model can be replaced with classifiers for better results.

🔄 Workflow

Dataset is defined in the backend

Model is trained using Linear Regression

Model is saved using Joblib

FastAPI loads the saved model

User submits input via HTML form

Prediction is displayed on the frontend

📁 Project Structure
fake-social-media-account-detector/
│
├── app.py              # FastAPI backend
├── train_model.py      # Model training script
├── model.pkl           # Saved model
├── requirements.txt
│
├── templates/
│   └── index.html      # Frontend
├── static/
│   └── style.css       # Styling
└── README.md

▶️ How to Run
pip install -r requirements.txt
python train_model.py
uvicorn app:app --reload


Open in browser:

http://127.0.0.1:8000

📌 Notes

This is a beginner-friendly ML project

Focuses on understanding ML + backend integration

Not intended for real-world deployment

👨‍💻 Author

Shawn D’Silva
BSc Cyber Security (Hons) – Computer Science
