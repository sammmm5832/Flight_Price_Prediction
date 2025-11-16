Airline Fare Prediction Using Machine Learning

This project builds a machine learning model to predict airline ticket prices based on flight-related features such as airline, route, number of stops, duration, and travel class. The goal is to analyze factors influencing ticket prices and develop an accurate predictive model using structured flight data.

OBJECTIVE:
To develop a predictive model that estimates airline ticket prices based on dataset features. The model should help users understand fare dynamics and provide accurate price predictions using regression techniques.

DATASET DETAILS
The dataset contains real-world flight information with the following key features:

Airline
Source city
Destination city
Date of journey (day and month extracted)
Departure time category
Arrival time category
Duration
Number of stops
Class
Price (target variable)

PREPROCESSING STEPS APPLIED:
Handling missing values
Extracting day and month from the journey date
Encoding categorical variables using Label Encoding
Removing duplicates
Cleaning duration format

ALGORITHM/MODEL USED
Two regression models were trained and compared:
Linear Regression
Random Forest Regression
The Random Forest model was selected as the final model based on superior accuracy and lower error metrics. The final trained model is saved as RandomForest_model.pkl.

RESULTS:
Accuracy, Graphs, etc.

MODEL PERFORMANCE ON THE TEST DATASET:

Linear Regression:
R² Score: approximately 0.90
Random Forest Regression:
R² Score: 0.9698
MAE: 2131.54
RMSE: 3944.68

Random Forest showed the best performance and was finalized for prediction.
Predictions were generated and saved as flight_price_predictions.csv.

CONCLUSION
The project successfully demonstrates that machine learning techniques can effectively model and predict airline ticket prices using structured flight features. Among the tested algorithms, Random Forest Regression achieved the highest accuracy and lowest error values. This confirms that ensemble learning methods handle mixed categorical and numerical features more effectively than simple linear models for this dataset.

FUTURE SCOPE:
Use larger and more diverse flight datasets
Incorporate additional variables such as seasonal trends and historical fare changes
Build a web application for real-time user predictions
Experiment with deep learning models for further improvements

REFERENCES
Airline fare prediction research papers
Machine learning regression model documentation
Scikit-learn official documentation
Articles on ensemble learning techniques
Standard preprocessing and feature engineering guidelines
