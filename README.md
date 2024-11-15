# Flask AQI Prediction

This is a Flask-based web application for predicting Air Quality Index (AQI) using a machine learning model. The project leverages data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) and applies data preprocessing, oversampling, and machine learning techniques to deliver accurate predictions through an intuitive web interface.

## Introduction

The Air Quality Index (AQI) is a critical metric that reflects air pollution levels and their potential health impacts. To create this application:

1. **Dataset**: I sourced the dataset from the UCI Machine Learning Repository, which includes various environmental parameters and their corresponding AQI values.
2. **Data Preprocessing**: 
   - Performed cleaning and normalization of data to handle missing or inconsistent values.
   - Applied **SMOTE (Synthetic Minority Oversampling Technique)** to address any class imbalance in the dataset.
3. **Model Development**:
   - Experimented with multiple machine learning algorithms such as Random Forest, Gradient Boosting, and Support Vector Machines.
   - Evaluated models using metrics like accuracy, precision, and F1-score.
   - Selected the best-performing model and saved it using `joblib` for deployment.
4. **Frontend**:
   - Designed the UI using **HTML** and **CSS**, ensuring a simple and responsive interface for input and output.
5. **Backend**:
   - Built the backend using **Flask**, which handles user inputs, model predictions, and results display.

This project combines data science and web development to provide a functional and user-friendly AQI prediction tool.

## Features

- **User-Friendly Interface**: Simple and interactive UI for inputting environmental parameters.
- **Real-Time AQI Prediction**: Predicts AQI based on user-provided data.
- **Pre-Trained Model**: Utilizes a trained machine learning model for accurate predictions.
- **Lightweight Web App**: Built using Flask for fast and efficient backend processing.

## Requirements

- Python 3.x
- Flask
- Scikit-learn
- Pandas
- NumPy
- SMOTE (via `imbalanced-learn`)
- Any additional dependencies (listed in `requirements.txt`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
