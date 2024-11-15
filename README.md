# Flask-based-UI-for-AQI-prediction
Flask AQI Prediction
This is a Flask-based web application for predicting Air Quality Index (AQI) using a machine learning model. The application provides a user-friendly interface to input relevant environmental parameters and receive the predicted AQI.

Features
Simple UI: User-friendly interface built using Flask.
AQI Prediction: Predicts AQI based on input features.
Interactive Input: Allows users to input environmental parameters such as temperature, humidity, etc.
Requirements
Python 3.x
Flask
Scikit-learn (or any other ML library used)
Pandas
Any additional dependencies as required by your project
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the application:

bash
Copy code
python app.py
Open the application in your browser:

arduino
Copy code
http://127.0.0.1:5000
Usage
Enter the required environmental parameters into the form.
Click the Predict AQI button.
View the predicted AQI on the results page.
Project Structure
php
Copy code
.
├── app.py                # Main Flask application
├── templates/            # HTML templates
│   ├── index.html        # Home page
│   └── result.html       # Results page
├── static/               # Static files (CSS, JS, images)
├── model/                # Machine learning model files
│   └── aqi_model.pkl     # Pretrained model
├── requirements.txt      # Dependencies
└── README.md             # Documentation
License
This project is licensed under the MIT License. Feel free to use and modify the code as per your needs.
