# Diabetes_prediction_using_ML

🩺 Diabetes Prediction Web App (Flask + ML)

This is a Flask web application that predicts the likelihood of a person having diabetes based on input health parameters. The backend is powered by a machine learning model (saved as Diabetes.pkl), and the frontend is built with HTML templates (index.html, result.html).
🚀 Features

    Accepts user input for 8 health-related factors (such as glucose level, BMI, age, etc.)

    Loads a pre-trained ML model (pickled using pickle)

    Predicts and displays the probability of diabetes on a result page

    Simple, responsive HTML UI with POST request handling

🧪 Technologies Used

    Flask (Python Web Framework)

    Pickle (Model serialization)

    Scikit-learn / pandas (ML + data handling)

    HTML/CSS for the frontend (templates: index.html, result.html)

⚙️ How to Use
1. Clone the repository

git clone https://github.com/your-username/diabetes-predictor-flask.git
cd diabetes-predictor-flask

2. Install the dependencies

pip install -r requirements.txt

3. Run the Flask app

python app.py

4. Open your browser

Visit http://127.0.0.1:5000 to access the app.
📝 Sample Input Fields

Make sure your HTML form in index.html contains input fields with name="1", "2", ..., "8", corresponding to:

    Number of Pregnancies

    Glucose

    Blood Pressure

    Skin Thickness

    Insulin

    BMI

    Diabetes Pedigree Function

    Age
