# Bengaluru-House-Price-Prediction

This Model/WebApp predicts real estate price in Bangalore. Many times we have come across websites like "Magicbricks.com" where they sell and estimate the price of the property in many part of the country, so this model is also inspired by the concept of predicting property prices based on the area, bedrooms, bathrooms and location. Firstly I built the model using sklearn and machine learning algorithm using Bangalore home prices dataset from kaggle.com. Second step was to write a python flask server that uses the saved model to serve http requests. Third component was the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price. During model building I came across all data science concepts such as data load and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tuning, k fold cross validation etc.

# Technologies used:

Python

Numpy and Pandas for data cleaning

Matplotlib for data visualization

Sklearn for model building

Jupyter notebook, visual studio code and pycharm as IDE
