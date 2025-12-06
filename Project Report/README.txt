# Traffic Accident Prediction in Calgary Using Weather Data

## Project Description

This project aims to predict traffic accidents in Calgary by analyzing the relationship between weather conditions and accident frequency. We combined historical traffic incident data with hourly weather observations to build machine learning models that identify which weather factors most significantly influence traffic safety. The analysis uses data from November 2025 and applies multiple predictive algorithms to determine when accidents are most likely to occur based on temperature, wind, visibility, precipitation, and other meteorological variables. The results show that certain times of day and specific weather conditions create higher risk scenarios, which can help traffic authorities implement targeted safety measures and better manage road conditions during hazardous weather.

## Approach

We preprocessed and merged traffic incident records with weather data on an hourly basis, then engineered 20 features including temporal patterns (hour of day, day of week) and weather indicators. Four machine learning models were trained and compared to identify the most effective approach for accident prediction. The model evaluation revealed that time of day is the strongest predictor of accidents, followed by atmospheric conditions like humidity and temperature.

## Technologies Used

Python, pandas, scikit-learn, matplotlib, and seaborn were used for data processing, model development, and visualization.