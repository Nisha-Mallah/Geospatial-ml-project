Project Title: Traffic Classification using Weather Data

This project is about predicting traffic levels (vehicle count categories) using weather data like temperature, humidity, wind speed, and precipitation.

What the project includes:

A Jupyter notebook (here-project.ipynb) where:

The data is preprocessed

A Random Forest model is trained

Hyperparameter tuning is done using GridSearchCV

The final model is saved using joblib

A saved model file: random_forest_model.pkl

A simple README.md file (this one)

Features used for prediction:

Humidity (%)

Wind Speed (km/h)

Temperature (C)

Rainfall

Snowfall

Target output:

Vehicle category (from 1 to 9)

Model details:

Random Forest Classifier

GridSearch used to find best parameters

Evaluation done using precision, recall, and F1-score

Requirements:

To run the notebook, install:

install:
scikit-learn  
pandas  
numpy  
joblib
You can install them using this command:

nginx
pip install scikit-learn pandas numpy joblib

How to use:

Open and run the here-project.ipynb notebook

The trained model will be saved as random_forest_model.pkl

To load and use the model:

python
Copy
Edit
import joblib
model = joblib.load('random_forest_model.pkl')
model.predict(X_test)

Author:
[Nisha Mallah]

