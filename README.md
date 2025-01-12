# Real-time-Weather-Prediction-using-Gradient-Boosting

This project is a Python-based weather prediction system that uses historical weather data and real-time data from the OpenWeatherMap API to predict future weather conditions, such as temperature and humidity. 
The project applies machine learning models, specifically Gradient Boosting Classifier and Regressor, to predict rain likelihood and future weather conditions.

This project combines historical weather data with real-time weather forecasts to make predictions about future weather conditions. It uses machine learning models to predict the likelihood of rain and future temperatures and humidity levels.

## Features
1. Real-Time Weather Data: Fetches live weather data from the OpenWeatherMap API.
2. Machine Learning Models: Uses Gradient Boosting Classifier for rain prediction and Gradient Boosting Regressor for temperature and humidity forecasting.
3. Data Preprocessing: Cleans and prepares historical data for training machine learning models.
4. Prediction Output: Provides future temperature and humidity predictions for the next five hours.

## Technologies Used
1. Python: Programming language.
2. Pandas: For data manipulation and analysis.
3. NumPy: For numerical computing.
4. Scikit-learn: For machine learning models and evaluation.
5. Requests: For making API requests.
6. pytz: For time zone conversions.

## How It Works
1. Data Retrieval: Fetches current weather data for the specified city using the OpenWeatherMap API.
2. Data Preparation: Reads and preprocesses historical weather data.
3. Model Training: Trains a Gradient Boosting Classifier to predict rain and a Gradient Boosting Regressor to forecast future temperatures and humidity.
4. Prediction: Uses trained models to predict future weather conditions for the next five hours.

## Future Enhancements
1. Extended Forecasting: Extend the prediction window beyond five hours.
2. Web Application: Develop a web-based interface for easier access.
3. Incorporate More Weather Features: Use additional weather features such as wind speed and precipitation.
