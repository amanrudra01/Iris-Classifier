Iris Classifier Web Application
This project implements an Iris species classifier using the K-Nearest Neighbors (KNN) algorithm. The application is built with Flask, a lightweight web framework for Python, and allows users to input flower measurements to predict the species of an Iris flower.

Features
Input Measurements: Enter Sepal Length, Sepal Width, Petal Length, and Petal Width.
Prediction: Get the predicted Iris species based on the input measurements.
Image Display: Display an image of the predicted Iris species.
Prerequisites
Python 3.x
Flask
Joblib
NumPy
Scikit-learn
Project Structure
app.py: The main Flask application file.
classifier.pkl: The trained KNN model saved using joblib.
templates/index.html: The HTML template for the main page.
static/IMG/: Contains the images corresponding to each Iris species.
requirements.txt: List of Python packages required to run the application.
Clone the Repository
bash
Copy code
git clone https://github.com/yourusername/iris-classifier.git
cd iris-classifier
Create a Virtual Environment
bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
Install Dependencies
bash
Copy code
pip install -r requirements.txt
Run the Flask App
bash
Copy code
python app.py
Access the Application
Open your web browser and go to http://0.0.0.0:8080.
