Smart Crop Prediction and Fertilizer Recommendation using Machine Learning
Overview
This project leverages machine learning to predict the most suitable crops for specific agricultural land based on various environmental and soil parameters, and recommends the appropriate type and amount of fertilizer required. 
By analyzing data such as soil type, weather conditions, and historical crop performance, the system helps farmers optimize their yield and sustainability.

Features
Crop Prediction: Recommends the best crop to plant based on soil and environmental conditions.
Fertilizer Recommendation: Suggests the type and amount of fertilizer needed for optimal crop growth.
User-Friendly Interface: Easy-to-use web interface for inputting data and viewing recommendations.
Data Visualization: Visual representation of data trends and predictions for better decision-making.

Installation
Prerequisites
Python 3.7 or later
pip (Python package installer)
Django 3.0 or later

Required Libraries
Install the necessary libraries using the following command:
pip install -r requirements.txt
requirements.txt:
numpy
pandas
scikit-learn
django
matplotlib
seaborn
xgboost

Setting Up
1.Clone the repository:
Git Clone https://github.com/Siddhishirole/-Smart-fertilizer-and-crop-recommendation-using-machine-learning./tree/master
2.Install the dependencies:
pip install -r requirements.txt
3.Set up the Django project:
python manage.py migrate
python manage.py createsuperuser
4.Start the Django development server:
python manage.py runserver
The application will be accessible at http://127.0.0.1:8000/.

Usage
Running the Application
To start the web application, run:
python manage.py runserver

Input Data
Users need to provide the following inputs for predictions:
Soil Type: Nitrogen, Phosphorous, potassium, pH, etc.
Weather Conditions: Temperature, humidity, rainfall, etc.
Historical Crop Data: Previous crop yields and performance metrics.

Interacting with the Application
Open a web browser and navigate to http://127.0.0.1:8000/.
Input the required data into the form.
Submit the form to receive crop and fertilizer recommendations.

Machine Learning Models
The project employs various machine learning algorithms to provide accurate predictions and recommendations:
Crop Prediction and fertilizer Recommendation: Uses Gaussian Naive Bayes Algorithm for its high performance data predictions.

Model Training
The models are trained on datasets containing features like soil properties, weather conditions, and crop yields. You can find sample datasets in the data/ directory and use utils.py to preprocess and train new models if needed.

Contribution
Contributions to the project are welcome. Please follow these steps:
1.Fork the repository.
2.Create a new branch for your feature or bugfix.
3.Commit your changes and push to your fork.
4.Submit a pull request with a detailed description of your changes
